


![jj](https://github.com/MeghanaSasanala/Patterns-python/assets/97938646/13c40814-479f-4a54-8c68-5324969cf053)



# Patterns Class Documentation

## Overview

The `Patterns` class provides methods to generate various patterns including square grids with different configurations.

## Class Methods

### `__init__(self, n)`

- **Description**: Initializes an instance of the `Patterns` class with the provided value of `n`.
  
- **Parameters**:
  - `n` (int): The size parameter used for generating patterns.

### `square_grid_pat_1(self)`

- **Description**: Generates a square grid pattern with asterisks (`*`).
  
- **Output Format**: Each row consists of `n` asterisks.

### `square_grid_num_pat_2(self)`

- **Description**: Generates a square grid pattern with numbers.
  
- **Output Format**: Each row contains numbers from 1 to `n`, repeated `n` times.

### `square_grid_num_pat_3(self)`

- **Description**: Generates a square grid pattern with numbers.
  
- **Output Format**: Each row contains numbers from 1 to `n`, incrementing by 1 in each column.

### `square_grid_alpha_pat_4(self)`

- **Description**: Generates a square grid pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by row index.

### `square_grid_alpha_pat_5(self)`

- **Description**: Generates a square grid pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by column index.

### `square_grid_num_pat_6(self)`

- **Description**: Generates a square grid pattern with numbers in decreasing order.
  
- **Output Format**: Each row contains numbers from `n` to 1, repeated `n` times.

### `square_grid_num_pat_7(self)`

- **Description**: Generates a square grid pattern with numbers in decreasing order.
  
- **Output Format**: Each row contains numbers from `n` to 1, decrementing by 1 in each column.

### `square_grid_alpha_pat_8(self)`

- **Description**: Generates a square grid pattern with uppercase alphabets in decreasing order.
  
- **Output Format**: Each row contains alphabets starting from the ASCII value of 'A' + `n` - 1 and decrementing by 1 in each column.

### `square_grid_alpha_pat_9(self)`

- **Description**: Generates a square grid pattern with uppercase alphabets in decreasing order based on column index.
  
- **Output Format**: Each row contains alphabets starting from the ASCII value of 'A' + `n` - column_index and decrementing by 1 in each column.

### `increasing_triangular_pat_10(self)`

- **Description**: Generates an increasing triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains increasing numbers of asterisks, starting from 1.

### `increasing_triangular_num_pat_11(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers from 1 to `n`, incrementing by 1 in each column.

### `increasing_triangular_num_pat_12(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers from 1 to `i`, where `i` is the row number.

### `increasing_triangular_alpha_pat_13(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from the ASCII value of 'A' + `i`, where `i` is the row number.

### `increasing_triangular_alpha_pat_14(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets based on column index.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by column index.

### `decreasing_triangular_pat_15(self)`

- **Description**: Generates a decreasing triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains decreasing numbers of asterisks, starting from `n` and decrementing by 1.

### `decreasing_triangular_num_pat_16(self)`

- **Description**: Generates a decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers from 1 to `n-1`, repeated `n-1` times.

### `decreasing_triangular_num_pat_17(self)`

- **Description**: Generates a decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from 1 and incrementing by 1, repeated `n-i` times, where `i` is the row number.

### `decreasing_triangular_alpha_pat_18(self)`

- **Description**: Generates a decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 1, repeated `n` times.

### `decreasing_triangular_alpha_pat_19(self)`

- **Description**: Generates a decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by column index.

### `decreasing_triangular_num_pat_20(self)`

- **Description**: Generates a decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains the row number `i`, repeated `i` times, where `i` is the row number.

### `decreasing_triangular_num_pat_21(self)`

- **Description**: Generates a decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from `n` and decrementing by 1, repeated `i` times, where `i` is the row number.

### `decreasing_triangular_alpha_pat_22(self)`

- **Description**: Generates a decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from the ASCII value of 'A' + `n-1` and repeating `i` times, where `i` is the row number.

### `decreasing_triangular_alpha_pat_23(self)`

- **Description**: Generates a decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from the ASCII value of 'A' + `n-j` and repeating `i` times, where `i` is the row number and `j` is the column index.

### `right_aligned_triangular_pat_24(self)`

- **Description**: Generates a right-aligned triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains increasing numbers of asterisks, right-aligned.

### `right_aligned_triangular_num_pat_25(self)`

- **Description**: Generates a right-aligned triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from 1 and incrementing by 1, right-aligned.

### `right_aligned_triangular_num_pat_26(self)`

- **Description**: Generates a right-aligned triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from 1 and incrementing by 1, right-aligned and vertically aligned.

### `right_aligned_triangular_alpha_pat_27(self)`

- **Description**: Generates a right-aligned triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 1, right-aligned.

### `right_aligned_triangular_alpha_pat_28(self)`

- **Description**: Generates a right-aligned triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 1, right-aligned and vertically aligned.

### `right_aligned_decreasing_triangular_pat_29(self)`

- **Description**: Generates a right-aligned decreasing triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains decreasing numbers of asterisks, right-aligned.

### `right_aligned_decreasing_triangular_num_pat_30(self)`

- **Description**: Generates a right-aligned decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from `n` and decrementing by 1, right-aligned and vertically aligned.

### `right_aligned_decreasing_triangular_num_pat_31(self)`

- **Description**: Generates a right-aligned decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from 1 and incrementing by 1, right-aligned and vertically aligned.

### `right_aligned_decreasing_triangular_alpha_pat_32(self)`

- **Description**: Generates a right-aligned decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' + `n-1` and decrementing by 1, right-aligned and vertically aligned.

### `right_aligned_decreasing_triangular_alpha_pat_33(self)`

- **Description**: Generates a right-aligned decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 1, right-aligned and vertically aligned.

### `increasing_triangular_pat_34(self)`

- **Description**: Generates an increasing triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains increasing numbers of asterisks, right-aligned.

### `increasing_triangular_num_pat_35(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from 1 and incrementing by 1, right-aligned and vertically aligned.

### `increasing_triangular_num_pat_36(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains odd numbers starting from 1 and incrementing by 2, right-aligned.

### `increasing_triangular_alpha_pat_37(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 1, right-aligned.

### `increasing_triangular_alpha_pat_38(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 2, right-aligned.

### `increasing_triangular_num_pat_39(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from 1 and incrementing by 1, right-aligned.

### `increasing_triangular_num_pat_40(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains odd numbers starting from the center and decrementing by 2, right-aligned.

### `increasing_triangular_alpha_pat_41(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 1, right-aligned.

### `increasing_triangular_alpha_pat_42(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 2, right-aligned.

### `increasing_triangular_num_pat_43(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from `n` and decrementing by 1, then incrementing by 1, left-aligned.

### `increasing_triangular_alpha_pat_44(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' + `n` and decrementing by 1, then incrementing by 1, right-aligned.

### `increasing_triangular_num_pat_45(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers starting from 1 and incrementing by 1, then decrementing by 1 (excluding the last number in the row), left-aligned.

### `increasing_triangular_alpha_pat_46(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' and incrementing by 1, then decrementing by 1 (excluding the last alphabet in the row), right-aligned.

### `alternating_triangular_pat_54(self)`

- **Description**: Generates an alternating triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains increasing numbers of asterisks, followed by decreasing numbers of asterisks, left-aligned.

### `alternating_triangular_num_pat_55(self)`

- **Description**: Generates an alternating triangular pattern with numbers.
  
- **Output Format**: Each row contains decreasing numbers starting from `n` and decrementing by 1, followed by increasing numbers starting from 1 and incrementing by 1, left-aligned.

### `alternating_triangular_num_pat_56(self)`

- **Description**: Generates an alternating triangular pattern with numbers.
  
- **Output Format**: Each row contains decreasing numbers starting from `n` and decrementing by 1, followed by decreasing numbers starting from `n` and decrementing by 1, left-aligned.

### `alternating_triangular_alpha_pat_57(self)`

- **Description**: Generates an alternating triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' + `n` and decrementing by 1, then incrementing by 1, left-aligned.

### `alternating_triangular_alpha_pat_58(self)`

- **Description**: Generates an alternating triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets starting from 'A' + `n` and decrementing by 1, then incrementing by 1, left-aligned.

### `left_pascal_triangle_pat_59(self)`

- **Description**: Generates a left-aligned Pascal's triangle pattern with asterisks (`*`).
  
- **Output Format**: Each row contains asterisks in increasing order, left-aligned.

### `left_pascal_triangle_num_pat_60(self)`

- **Description**: Generates a left-aligned Pascal's triangle pattern with numbers.
  
- **Output Format**: Each row contains numbers in decreasing order, left-aligned.

### `left_pascal_triangle_num_pat_61(self)`

- **Description**: Generates a left-aligned Pascal's triangle pattern with numbers.
  
- **Output Format**: Each row contains numbers in increasing order, left-aligned.

### `left_pascal_triangle_alpha_pat_62(self)`

- **Description**: Generates a left-aligned Pascal's triangle pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets in increasing order, left-aligned.

### `left_pascal_triangle_alpha_pat_63(self)`

- **Description**: Generates a left-aligned Pascal's triangle pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets in decreasing order, left-aligned.

### `increasing_triangular_pat_64(self)`

- **Description**: Generates an increasing triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains asterisks in increasing order, left-aligned.

### `increasing_triangular_num_pat_65(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers in increasing order, left-aligned.

### `increasing_triangular_num_pat_66(self)`

- **Description**: Generates an increasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers in increasing order, left-aligned.

### `increasing_triangular_alpha_pat_67(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets in increasing order, left-aligned.

### `increasing_triangular_alpha_pat_68(self)`

- **Description**: Generates an increasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets in increasing order, left-aligned.

### `decreasing_triangular_pat_69(self)`

- **Description**: Generates a decreasing triangular pattern with asterisks (`*`).
  
- **Output Format**: Each row contains asterisks in decreasing order, left-aligned.

### `decreasing_triangular_num_pat_70(self)`

- **Description**: Generates a decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers in decreasing order, left-aligned.

### `decreasing_triangular_num_pat_71(self)`

- **Description**: Generates a decreasing triangular pattern with numbers.
  
- **Output Format**: Each row contains numbers in decreasing order, left-aligned.

### `decreasing_triangular_alpha_pat_72(self)`

- **Description**: Generates a decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets in decreasing order, left-aligned.

### `decreasing_triangular_alpha_pat_73(self)`

- **Description**: Generates a decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets in decreasing order, left-aligned.

### `decreasing_triangular_alpha_pat_74(self)`

- **Description**: Generates a decreasing triangular pattern with uppercase alphabets.
  
- **Output Format**: Each row contains alphabets in increasing order, left-aligned.

### `diamond_pat_75(self)`

- **Description**: Generates a diamond pattern with asterisks (`*`).
  
- **Output Format**: The diamond is formed by asterisks in increasing order in the first half and decreasing order in the second half, center-aligned.

### `diamond_num_pat_76(self)`

- **Description**: Generates a diamond pattern with numbers.
  
- **Output Format**: The diamond is formed by numbers in increasing order in the first half and decreasing order in the second half, center-aligned.

### `diamond_num_pat_77(self)`

- **Description**: Generates a diamond pattern with numbers.
  
- **Output Format**: The diamond is formed by numbers in increasing order in the first half and decreasing order in the second half, center-aligned, with each row starting from 1.

### `diamond_num_pat_78(self)`

- **Description**: Generates a diamond pattern with numbers.
  
- **Output Format**: The diamond is formed by numbers in increasing order in the first half and decreasing order in the second half, center-aligned.

### `diamond_alpha_pat_79(self)`

- **Description**: Generates a diamond pattern with uppercase alphabets.
  
- **Output Format**: The diamond is formed by alphabets in increasing order in the first half and decreasing order in the second half, center-aligned.

### `diamond_alpha_pat_80(self)`

- **Description**: Generates a diamond pattern with uppercase alphabets.
  
- **Output Format**: The diamond is formed by alphabets in increasing order in the first half and decreasing order in the second half, center-aligned.

### `inverted_v_shaped_pat_81(self)`

- **Description**: Generates an inverted V-shaped pattern with asterisks (`*`).
  
- **Output Format**: The pattern resembles an inverted V shape formed by asterisks, center-aligned.

### `inverted_v_shaped_num_pat_82(self)`

- **Description**: Generates an inverted V-shaped pattern with numbers.
  
- **Output Format**: The pattern resembles an inverted V shape formed by numbers, center-aligned.

### `inverted_v_shaped_num_pat_83(self)`

- **Description**: Generates an inverted V-shaped pattern with numbers.
  
- **Output Format**: The pattern resembles an inverted V shape formed by numbers, center-aligned.

### `inverted_v_shaped_alpha_pat_84(self)`

- **Description**: Generates an inverted V-shaped pattern with uppercase alphabets.
  
- **Output Format**: The pattern resembles an inverted V shape formed by alphabets, center-aligned.

### `inverted_v_shaped_alpha_pat_85(self)`

- **Description**: Generates an inverted V-shaped pattern with uppercase alphabets.
  
- **Output Format**: The pattern resembles an inverted V shape formed by alphabets, center-aligned.

### `v_shaped_pat_86(self)`

- **Description**: Generates a V-shaped pattern with asterisks (`*`).

- **Output Format**: The pattern resembles a V shape formed by asterisks, center-aligned.

### `v_shaped_num_pat_87(self)`

- **Description**: Generates a V-shaped pattern with numbers.

- **Output Format**: The pattern resembles a V shape formed by numbers, center-aligned.

### `v_shaped_num_pat_88(self)`

- **Description**: Generates a V-shaped pattern with numbers.

- **Output Format**: The pattern resembles a V shape formed by numbers, center-aligned.

### `v_shaped_alpha_pat_89(self)`

- **Description**: Generates a V-shaped pattern with uppercase alphabets.

- **Output Format**: The pattern resembles a V shape formed by alphabets, center-aligned.

### `v_shaped_alpha_pat_90(self)`

- **Description**: Generates a V-shaped pattern with uppercase alphabets.

- **Output Format**: The pattern resembles a V shape formed by alphabets, center-aligned.

### `hallow_diamond_pat_91(self)`

- **Description**: Generates a hollow diamond pattern with asterisks (`*`).

- **Output Format**: The diamond is formed by asterisks, with empty spaces inside, center-aligned.

### `hallow_diamond_num_pat_92(self)`

- **Description**: Generates a hollow diamond pattern with numbers.

- **Output Format**: The diamond is formed by numbers, with empty spaces inside, center-aligned.

### `hallow_diamond_num_pat_93(self)`

- **Description**: Generates a hollow diamond pattern with numbers.

- **Output Format**: The diamond is formed by numbers, with empty spaces inside, center-aligned.

### `hallow_diamond_alpha_pat_94(self)`

- **Description**: Generates a hollow diamond pattern with uppercase alphabets.

- **Output Format**: The diamond is formed by alphabets, with empty spaces inside, center-aligned.

### `hallow_diamond_alpha_pat_95(self)`

- **Description**: Generates a hollow diamond pattern with uppercase alphabets.

- **Output Format**: The diamond is formed by alphabets, with empty spaces inside, center-aligned.

### `half_diamond_with_increasing_space_96(self)`

- **Description**: Generates a half diamond pattern with increasing spaces.

- **Output Format**: The pattern resembles a half diamond shape formed by asterisks, with increasing spaces, center-aligned.

### `decreasing_space_diamond_pattern_97(self)`

- **Description**: Generates a diamond pattern with decreasing spaces.

- **Output Format**: The pattern resembles a diamond shape formed by asterisks, with decreasing spaces, center-aligned.

### `mirrored_diamond_98(self)`

- **Description**: Generates a mirrored diamond pattern.

- **Output Format**: The pattern resembles a diamond shape formed by asterisks, mirrored vertically, center-aligned.

### `symmetrical_triangular_pat_99(self)`

- **Description**: Generates a symmetrical triangular pattern.

- **Output Format**: The pattern resembles a symmetrical triangular shape formed by asterisks, center-aligned.

### `symmetrical_triangular_pat_100(self)`

- **Description**: Generates a symmetrical triangular pattern.

- **Output Format**: The pattern resembles a symmetrical triangular shape formed by asterisks, center-aligned.




# star codes
This is my first repository 
<br>
Author-Sneha
def print_s_pattern(size):
    """
    Prints the letter 'S' using stars (*) with the given size.
    
    Parameters:
    size (int): The size of the pattern (height of the S).
    """
    for row in range(size):
        if row == 0 or row == size // 2 or row == size - 1:
            print('*' * size)  # Print full row of stars for the top, middle, and bottom
        elif row < size // 2:
            print('*')  # Print stars on the left for the top half
        else:
            print(' ' * (size - 1) + '*')  # Print stars on the right for the bottom half

# Example Usage
size = 7  # Height of the "S"
print_s_pattern(size)

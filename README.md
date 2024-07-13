# reverse
# Function to reverse a string
def reverse_string(s):
    return s[::-1]

# Ask the user for a string
user_string = input("Enter a string: ")

# Reverse the string
reversed_string = reverse_string(user_string)

# Print the reversed string
print(f"The reversed string is: {reversed_string}")

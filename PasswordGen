import random
import string


def generate_password(length=256):
    # Define the characters to use for password generation
    characters = string.ascii_letters + string.digits + string.punctuation

    # Generate a random password by selecting characters randomly from the pool
    password = ''.join(random.choice(characters) for _ in range(length))

    return password

def get_pass():
    # Prompt the user to enter the desired length of the password
    length = int(input("Enter the length of the password: "))

    # Generate the password
    password = generate_password(length)

    # Display the generated password
    print("Generated Password:", password)
    

get_pass()


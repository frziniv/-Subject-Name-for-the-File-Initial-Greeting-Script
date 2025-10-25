# -Subject-Name-for-the-File-Initial-Greeting-Script
# Simple script to greet the world and GitHub.

def greet():
    message = "Hello, GitHub! This is my first file in the new repository."
    print(message)

# Simple script to greet the world and GitHub.

def greet(user_name="User"):
    # Updated message to include a specific name.
    message = f"Hello, GitHub! This is my first file in the new repository. Glad to have you here, {user_name}!"
    print(message)

if __name__ == "__main__":
    # Passing a placeholder name for the first run.
    greet(user_name="New Contributor")    greet()

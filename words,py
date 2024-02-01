def count(input_text):
    words=input_text.split()
    return len(words)
try:
    user=input("Enter text : ")
    if not user:
        raise ValueError("Input cannot be empty")
    word_count=count(user)
    print("Word count ",word_count)
except ValueError as ve:
    print("Error",ve)
except Exception as e:
    print("Unxpected error",e)
def check_odd_or_even(number):
    if number % 2 == 0:
        return f"{number} is an Even number."
    else:
        return f"{number} is an Odd number."
try:
    user_input = int(input("Enter a number: "))
    result = check_odd_or_even(user_input)
    print(result)
except ValueError:
    print("Please enter a valid integer.")

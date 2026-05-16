# Program title
print("========= Temperature Calculator =========")

# Menu options
print("1. Fahrenheit to Celsius\n2. Celsius to Fahrenheit")

# Separator line
print("-----------------------------------")

# User selects option
option = int(input("Choose the option above 1 or 2 : "))

# Separator line
print("===================================")

# Fahrenheit to Celsius
if (option == 1):
    # Input Fahrenheit
    Fahrenheit = float(input("Enter the Fahrenheit : "))
    # Convert to Celsius
    Celsius = (Fahrenheit - 32) * 5/9
    # Print result
    print("Celsius :", round(Celsius,2))

# Celsius to Fahrenheit
elif (option == 2):
    # Input Celsius
    Celsius = float(input("Enter the Celsius : "))
    # Convert to Fahrenheit
    Fahrenheit = (Celsius * 9/5) + 32
    # Print result
    print("Fahrenheit :", round(Fahrenheit,2))

# Invalid option
else:
    print("Error: Invalid option")
    print("Try again")

# End line
print("-----------------------------------")
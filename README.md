# Temperature-conversion-program-
unit = input("is the temperature in Celsius or Fahrenheit? (C or F): ")
temperature = float(input("Enter the temperature: "))
if unit.upper() == "C":
    temperature = (9*temperature)/5+32
    print(f"The temperature in Fahrenheit is:{round(temperature,1)}F")
elif unit.upper() == "F":
    temperature = (temperature-32)*5/9
    print(f"The temperature in Celsius is: {round(temperature,1)} C")
else:
    print(f"{unit} is not a valid unit of measurement.")

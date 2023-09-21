radius_str = input("Enter the radius of the circle: ")
try:
    radius = float(radius_str)
except ValueError:
    print("Invalid input. Please enter a valid number for the radius.")
    exit()
area = 3.14159265359 * radius ** 2  
print(f"The area of the circle with radius {radius} is {area:.2f}")

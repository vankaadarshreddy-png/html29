# Square pattern of asterisks
size = int(input("Enter size of square: "))

for row in range(size):          # Outer loop controls rows
    for col in range(size):      # Inner loop controls columns
        print("*", end=" ")
    print()                      # Move to next line after each row
✅ Example (size = 5):

Code
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
2️⃣ Right-Angled Triangle of Numbers
python
# Right-angled triangle with numbers
height = int(input("Enter height of triangle: "))
num = 1

for row in range(1, height + 1):     # Outer loop controls rows
    for col in range(row):           # Inner loop prints numbers in each row
        print(num, end=" ")
        num += 1
    print()                          # Move to next line after each row
✅ Example (height = 5):

Code
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
3️⃣ Pyramid Pattern of Asterisks
python
# Pyramid pattern of asterisks
height = int(input("Enter height of pyramid: "))

for row in range(height):                     # Outer loop controls rows
    # Print spaces before stars
    for space in range(height - row - 1):
        print(" ", end=" ")
    # Print stars
    for star in range(2 * row + 1):
        print("*", end=" ")
    print()                                   # Move to next line
✅ Example (height = 5):

Code
        * 
      * * * 
    * * * * * 
  * * * * * * * 
* * * * * * * * * 

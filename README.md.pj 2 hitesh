print("Welcome to the Pattern Generator and Number Analyzer!")

while True:

    print("\n1. Generate a Pattern")
    print("2. Analyze a Range of Numbers")
    print("3. Exit")

    choice = int(input("Enter your choice: "))

    if choice == 1:

        rows = int(input("Enter the number of rows: "))

        print("\nPattern:\n")

        for i in range(1, rows + 1):
            for j in range(i):
                print("*", end="")
            print()

    elif choice == 2:

        start = int(input("Enter the start of the range: "))
        end = int(input("Enter the end of the range: "))

        total = 0

        for i in range(start, end + 1):

            if i < 0:
                continue

            if i % 2 == 0:
                print("Number", i, "is Even")
            else:
                print("Number", i, "is Odd")

            total = total + i

            if total < 0:
                pass

        print("Sum of all numbers from", start, "to", end, "is:", total)

    elif choice == 3:
        print("Exiting the program. Goodbye!")
        break

    else:
        print("Invalid Choice!")

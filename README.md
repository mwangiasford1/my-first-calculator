def calculator():
           
    num1 = float(input("enter the first number"))
    num2 = float(input("enter the second number"))
    operation = input("enter an operation(+, -, *, /):")

    if operation == '+':
        result = num1 + num2
        print(f"{num1} + {num2} = {result}")

    elif operation == '-':
        result = num1 - num2
        print(f"{num1} - {num2} = {result}")

    elif operation =='*':
        result = num1 * num2
        print(f"{num1} * {num2} = {result}")

    elif operation =='/':
        result = num1 / num2
        if num2 == 0:
            print ("Error: Division not allowed.")
        else:
            result = num1 / num2
            print(f"{num1} / {num2} = {result}")
    else:
        print("Invalid operation. Please enter one of +, -, *, or /.")
    
        print("Invalid input. please enter numerical values.")
        
     
calculator()

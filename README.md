# Practicerepo.anu
This is my first git Repo.

user = input("Enter the arithmetic operation that you want to perform")


if user == "sum":
    a = int(input('Enter the first number:' ))
    b = int(input('Enter the second number:' ))
    c = int(input('Enter the third number:' ))
    d = int(input('Enter the fourth number:' ))
    e = int(input('Enter the fifth number:' ))
    result = a + b + c + d + e
    print("The sum of your inputs is:")
    print(result)
    

elif user == "diff":
    a = int(input('Enter the first number:' ))
    b = int(input('Enter the second number:' ))
    result = a-b
    print("The difference for your inputs is:")
    print(result)

elif user == "multiply":
    if a != 0 and b != 0 and c!=0 and d!=0 and e!=0:
        result = a * b * c * d * e
        print("The product of your inputs is:")
        print(result)
    else :
        print("Kindly enter a non zero number in the place where you have given zero/zeroes:")

elif user == "division":
    a = int(input('Enter the first number:' ))
    b = int(input('Enter the second number:' ))
    if b != 0:
        result = a/b
        print("The quotient of your inputs is:")
        print(result)
    else :
         print("Kindly give a non-zero denominator")

elif user == "percentage":
    numerator = int(input('Enter the numerator:' ))
    denominator = int(input('Enter the second denominator:' ))
    if denominator != 0:
        result = (numerator / denominator) * 100
        print("The percentage you are looking for is:")
        print(result,"%")
    else :
         print("Kindly give a non-zero denominator")


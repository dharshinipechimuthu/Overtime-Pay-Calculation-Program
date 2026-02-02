# Overtime-Pay-Calculation-Program

total_overtime_pay = 0

for i in range(1, 11):
    h = int(input(f"Enter Working Hours of Emp {i} : "))
    if h > 40:
        extra = h - 40
        ovpay = extra * 12
        print(f"Over time pay of emp {i} is {ovpay}")
        total_overtime_pay += ovpay
    else:
        print("No Overtime Pay")

print("Total Overtime Pay of all employees :", total_overtime_pay)

Output:
Enter Working Hours of Emp 1 : 43
Over time pay of emp 1 is 36
Enter Working Hours of Emp 2 : 44
Over time pay of emp 2 is 48
Enter Working Hours of Emp 3 : 41
Over time pay of emp 3 is 12
Enter Working Hours of Emp 4 : 40
No Overtime Pay
Enter Working Hours of Emp 5 : 42
Over time pay of emp 5 is 24
Enter Working Hours of Emp 6 : 44
Over time pay of emp 6 is 48
Enter Working Hours of Emp 7 : 56
Over time pay of emp 7 is 192
Enter Working Hours of Emp 8 : 43
Over time pay of emp 8 is 36
Enter Working Hours of Emp 9 : 44
Over time pay of emp 9 is 48
Enter Working Hours of Emp 10 : 40
No Overtime Pay
Total Overtime Pay of all employees : 444

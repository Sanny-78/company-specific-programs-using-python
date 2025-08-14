#problem statement -1 (prime number)
n = int(input())
if n > 1:
    for i in range(2, n):
        if n % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime")
else:
    print("Not prime")
    <img width="1625" height="334" alt="Screenshot 2025-08-13 194728" src="https://github.com/user-attachments/assets/34607300-5e80-4ea6-aa1e-7ef4b2a561ab" />
#problem statement-2(reverse string)
s=input()
print(s[::-1])
<img width="1635" height="195" alt="Screenshot 2025-08-13 210643" src="https://github.com/user-attachments/assets/b3ac8bb0-7e8f-422a-af4f-7948251c5362" />
#problem statement-3(arithmetic operations)
a = 5
b =2
print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)        
print("Floor Division:", a // b) 
print("Modulus:", a % b)         
print("Exponent:", a ** b)       
<img width="1636" height="325" alt="Screenshot 2025-08-13 212004" src="https://github.com/user-attachments/assets/e21e8223-ac96-4130-8134-0a12881d27bb" />

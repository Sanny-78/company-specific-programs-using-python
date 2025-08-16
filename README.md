@problem statement-1(multiplication table)
n=int(input("enter a number"))
for i in range(1,11):
print(n,"x",i,"=",n*i)
<img width="1917" height="401" alt="Screenshot 2025-08-16 064846" src="https://github.com/user-attachments/assets/755c017b-0e29-40dd-a236-e7fe7ddf3aed" />
@problem statement-1.1(square of a number)
n=int(input("enter a number: "))
print("square=",n*n)
<img width="1918" height="355" alt="Screenshot 2025-08-16 065557" src="https://github.com/user-attachments/assets/2aebe75e-448f-4f76-972f-514cdc703ca7" />
@problem statement-2(count words in a sentence)
s = input("Enter a sentence: ")
print("Words =", len(s.split()))
<img width="1684" height="229" alt="Screenshot 2025-08-16 073109" src="https://github.com/user-attachments/assets/5452dfe5-6081-434f-91d5-3060e0d720ac" />
@problem statement-2.1(count digits)
n = int(input("Enter a number: "))
print("Digits =", len(str(n)))
<img width="1684" height="229" alt="Screenshot 2025-08-16 073109" src="https://github.com/user-attachments/assets/b619c150-befd-4f4e-bb62-91684e40fb69" />
@problem statement-3( first n prime numbers)
n = int(input("Enter how many primes: "))
count, num = 0, 2
while count < n:
    for i in range(2, num):
        if num % i == 0:
            break
    else:
        print(num)
        count += 1
    num += 1
    <img width="1708" height="778" alt="Screenshot 2025-08-16 073936" src="https://github.com/user-attachments/assets/c11f8e7e-7659-495d-8101-71aca7bac4b0" />
@problem statement-4(sum digits)
n = input("Enter a number: ")
s = 0
for digit in n:
    s += int(digit)
print("Sum of digits =", s)
<img width="1629" height="280" alt="Screenshot 2025-08-16 074244" src="https://github.com/user-attachments/assets/b7202c8a-f49f-4359-9d41-dfccac08e689" />

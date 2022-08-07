# Dcit-104-assignment-

def sum_prime(max):
    sum = 0
    is_prime = True
    for num in range(2, max + 1):
        i = 2
        for i in range(2, num):
            if num % i == 0:
                i = num
                break

        if i is not num:
            sum = sum + num
    print(sum)

sum_prime(10)

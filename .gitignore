def is_prime(num: int) -> bool:
    """Checks whether the number is prime or not"""
    """att : prime number is a number which is only divisible by one and itself"""
    for i in range(2, (num // 2) + 1):
        # To check the divisibility of a number, it is enough to move to half of it
        if num % i == 0:
            return False
    # if there is no number which divisible into the given number so it is prime
    return True


# finding prime numbers between 100-1000
counter = 1  # count of prime numbers
for number in range(100, 1000):
    if is_prime(number):
        print(counter, number)
        counter += 1

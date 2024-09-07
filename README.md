# PATTERN-OF-STARS
def print_pattern(num):
    for i in range(1, num + 1):
        print("*" * i)
        
num = int(input("Enter a number: "))        
print("Pattern for input", num, ":")
print_pattern(num)

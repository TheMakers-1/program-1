# program-1
#factorial
def fac(number):
    output = 1

    for i in range(1, number + 1):
        output *= i
    
    return output

out = input("input>")

out = int(out)

print("factorial value is {}.".format(fac(out)))

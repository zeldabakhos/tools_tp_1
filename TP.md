CONTRIBUTORS = ["Zelda Bakhos", "Oscar Daniel Camargo","Zakaria TIBTIBA"] # Conflicts generator 1

def add(a, b):
    return a + b

def subtract(a, b):
    pass

def multiply(a, b):
    return a * b

def divide(a, b):
	c = a/b
	return(c)

if __name__ == "__main__":
    print(f"Welcome to the Group Calculator!, written by {CONTRIBUTORS}")
    print(add(2+2)) # Conflicts generator 2
    print(divide(10,5))
    print("multiply_test", multiply(3, 4))

# Python_programs
Program Name Is Arithmetic


def Addition(value1, value2):
	ret = value1 + value2
	return ret

def main():
	no1 = int(input("Enter first number"))
	no2 = int(input("Enter second number"))

	ans = Addition(no1,no2)
	print("Addition is : ",ans)
	

if __name__ == "__main__":
	main()

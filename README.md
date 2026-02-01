# 92.-Separate-Positive-and-Negative-Numbers-in-a-List
NumList = []
Positive = []
Negative = []

Number = int(input("Please enter the Total Number of List Elements : "))
for i in range(1, Number + 1):
    value = int(input(f"Please enter the Value of {i} Element : "))
    NumList.append(value)

for j in range(Number):
    if NumList[j] >= 0:
        Positive.append(NumList[j])
    else:
        Negative.append(NumList[j])

print("Element in Positive List is : ", Positive)
print("Element in Negative List is : ", Negative)

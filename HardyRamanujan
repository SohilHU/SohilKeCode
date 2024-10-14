# print(99)
count=0
sum=0
# for i in range (1729,1000):
#     count=0
#     max=int(i**(1/3))+1
#     for j in range (1,max):
#         for k in range (j,max):
#             sum=j**3+k**3
#             if sum==i:
#                 count+=1
#                 if count==2:
#                     print(i)
# for j in range(1, max):
#         for k in range(j, max):
#             if j**3 + k**3 == i:
#                 count += 1
#                 if count == 2:  # If found two ways, print the number
#                     print(i)
#                     break  # Stop further checks for this number

for i in range(1000, 500000):  # Check numbers from 1000 to 9999
    count = 0  # Reset count for each number
    max_limit = int(i**(1/3)) + 1  # Upper bound for cubes

    for j in range(1, max_limit):
        for k in range(j, max_limit):
            if j**3 + k**3 == i:
                count += 1
                if count == 2:  # If found two ways, print the number
                    print(i)
                    break  # Stop further checks for this number

# Print-all-Even-Numbers-in-a-Range---Python

Using range() with Step

The built-in range() function can also be used efficiently to print even numbers by setting a step value of 2. This avoids the need for an extra if condition.

example:

s = 1
e = 10

for i in range(2, e + 1, 2):

    print(i)

output:
2
4
6
8
10




Using range() without Step

In this method we iterate through each number in the range and check divisibility by 2 using an if statement.

The condition i % 2 == 0 ensures only even numbers are included in the list.

example:

for number in range(2, 11):

    if number % 2 == 0:
    
        print(number)


output:
2
4
6
8
10
        


    

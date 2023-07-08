1.Finding the percentage:-


if __name__ == '__main__':

    n = int(input())

    student_marks = {}

    for _ in range(n):

        name, *line = input().split()

        scores = list(map(float, line))

        student_marks[name] = scores

    query_name = input()

    l1 = list(student_marks[query_name]) 

    addition = sum(l1)

    result = addition/len(l1)

    print('%.2f'% result)

Question 2:-

def split_and_join(line):

    # write your code here

    a = line.split(" ")

    b = "-".join(a)

    return(b)


if __name__ == '__main__':

    line = input()

    result = split_and_join(line)

    print(result)
    
Question 3:-

n, set_n, b, set_b = int(input()), set(input().split()), int(input()), set(input().split())
print(len(set_n.union(set_b)))

Question 4:-
if __name__ == '__main__':
    n = int(input())
    arr = list(map(int, input().split()))
    arr1 = set(arr)
    arr2 = sorted(arr1)
    print(arr2[-2])


Question 5:-

def swap_case(s):

    string = ""

    for i in s:

        if i.isupper() == True:

            string+=(i.lower())

        else:

            string+=(i.upper())

    return string


if __name__ == '__main__':

    s = input()

    result = swap_case(s)

    print(result)


print(len(set_n.intersection(set_b)))

Question 6:-

if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a+b)
    print(a-b)
    print(a*b)


Question 7:-

if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a//b)
    print(a/b)











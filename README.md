# Fit-Squares-in-Triangle
What is the maximum number of squares of size 2x2 that can be fit in a right angled isosceles triangle of base B. One side of the square must be parallel to the base of the isosceles triangle. Base is the shortest side of the triangle

t=int(input())
for i in range(t):
    n=int(input())
    s=0
    for i in range(1,n//2):
        s+=i
    print(s)

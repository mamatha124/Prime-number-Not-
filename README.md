# Prime-number-Not in python
# Approach-1
n = int(input())
c = 0
for i in range(1,n+1):
  if n%i == 0:
    c = c + 1
if c == 2:
  print("Prime Number")
else:
  print("Not a Prime number")
# Approach-2
n = int(input())
k = 0
for i in range(2,n):
  if n%i == 0:
    k = 1
    break
if k == 1:
  print("Not Prime")
else:
  print("Prime")

# 4week

# --------------python study--------------
s = [1, 3, 5, 7, 9]
t = [2, 4, 6, 8]
a = zip(s,t)
print(a)


for x,y in a:
    print(x,y)

# ----------------------------------------
fin = open('c://users/rhksv/desktop/pystudy/input.txt')
for i in range(10000):
    a = fin.readline()
    print(a)
    if a == '\n': break

fin.close()

# ----------------------------------------
fin = open('c://users/rhksv/desktop/pystudy/input.txt')
a = fin.readline()

while a:
    print(a)
    a=fin.readline()
    
fin.close()

# ----------------------------------------
fin = open('c://users/rhksv/desktop/pystudy/input.txt')
a = fin.readlines()
for i in a:
    print(i)

fin.close()

# ----------------------------------------
fin = open('c://users/rhksv/desktop/pystudy/input.txt')
a = fin.readlines()
for i in a:
    s = i.split()
    for j in s:
        print(int(j)*5)
fin.close()

# ----------------------------------------
fin = open('c://users/rhksv/desktop/pystudy/input.txt')
a = fin.readlines()
for i in a:
    s = map(int, i.split())
    for j in s:
        print(j*5)
    
    
fin.close()

# ----------------------------------------
a = map(int, '1 2 3'.split())
s = sum(a)
print(s)
for i in a:
    print(i)
print(a)

# ----------------------------------------
for i in range(2):
    for j in range(3):
        print(i, j)

# ----------------------------------------
a=[0,0,0,0,0] 
a[2]=3
print(a)

# ----------------------------------------
a = [0]*10 # 10번 반복을 의미함함
a[2] = 3
print(a)

# ----------------------------------------
a = [[0]*5]*3
a[1][2]=3
print(a)






























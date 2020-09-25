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


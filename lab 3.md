# lab_3n = int(input())
print("В первый день фирма реализовала,"+str(n)+" тыс.руб")
q = int(input())
print("Сумма к которой тсремиться фирма"+str(q)+" тыс.руб")
A = (n/100)*3
s = int(float(print("Дни "+str((q/A + q/(n+A))/2))))
c = n
X = []
for i in range(s):
      c +=A
      X.append(c)
for i in range(s):
      print(X[i])

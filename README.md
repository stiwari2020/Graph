import matplotlib.pyplot as plt

num=12345











mylist=[]
while(num !=1):
  mylist.append(int(num))
  if (num%2)==0:
    num=num/2
  else:
    num=num*3+1
mylist.append(1) 
plt.plot(mylist)
print(mylist)

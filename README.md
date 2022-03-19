# assignment1-17-03-22
string
s=input("enter the string")
l=list(s)
x=[]
for i in l:
    if i=='a' or i=='e' or i=='i' or i=='o' or i=='u':
        continue
    else:
        x.append(i)
    for i in x:
        print(i,end=" ")
output:
enter the stringumbrella
m m b m b r m b r l m b r l l 

print("Enter The Array's Numbers:")
array=list(map(int,input().split()))
result=[]
ind=0
for x in range(len(array)):
	sum=0
	
	while array[ind] > 0:
		sum+=array[ind]
		array[ind]-=1
	
	ind+=1
	result.append(sum)
for x in result : 
	print(x)

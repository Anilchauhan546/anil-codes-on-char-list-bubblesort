# anil-codes-on-char-list-bubblesort

#printing each character in a list

lst=['Anil ','sunil ','sri ram']
for char in lst:
    # print(char)
    for c in char:
        print(c)

# Unpacking dictionary using while in python

data={'name':'Anil','role':'Data Engineer','Firm':'5DataINC','experience':'3 Months'}

dil=list(data.items())
i=0
while i<len(dil):
   key,value=dil[i]
   print(key,"=",value)
   i+=1

   dictionary={'name':'Anil','age':22,'firm':'5DataINC'}

di_to_list=list(dictionary.items())

i=0
while i<len(di_to_list):
    key,value=di_to_list[i]
    print(key,"=",value)
    i+=1

# bubble sort on a list


list=['Google','Capgemini','Cognizant','Accenture','Amadeus','DeltaX']
n=len(list)
for i in range(n-1):
    for j in range(n-i-1):
        if list[j]>list[j+1]:
            list[j],list[j+1]=list[j+1],list[j]
print(list)

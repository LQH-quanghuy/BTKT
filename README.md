Câu 1:
  a = int(input('Nhập số a: '))
  if a%2 == 0:
    print('Đây là số chẵn')
  else:
    print("Đây là số lẻ") 
    
Câu 2:
def KT_songuyento(n):
  for i in range(2,n):
     if n % i == 0:
       return False
       return True
while True:
   n = int(input("Hãy nhập vào 1 số nguyên tố duy nhất: ")) 
   if KT_songuyento(n) == True:
       print("Đây là số nguyên tố")
   elif KT_songuyento(n) == False:
     print("Xin hãy nhập lại:")
   else:
     break
     
Câu 3:
array=[1,2,3,4,5,6]
def inverse_array(k):
  array.reverse()
  print(array)
inverse_array(array)

Câu 4: 
import math
def fibonacci(n):
    if (n < 0):
        return -1
    elif (n == 0 or n == 1):
        return n
    else:
        return fibonacci(n - 1) + fibonacci(n - 2)

n = int(input("Nhập một số nguyên dương n = "))
print (" Các số fibonaci nhỏ hơn",n)
i = 0
fin = fibonacci(i)
while(fin < n):
    fin = fibonacci(i)
    if (fin < n):
        print(fin)
        i = i + 1

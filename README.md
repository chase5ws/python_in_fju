nm1 = eval(input("enter nm1="))
nm2 = eval(input("enter another nm2="))

tol = nm1 + nm2
ave = tol/2

print("nm1 =",nm1,"nm2 =",nm2)
print("tol =",tol,"ave =",ave)
"""
#print(format(1.22,"5.1f"))
#在format裡面給予5格並取浮點數第1位

#print("%10d"%(123))
#在print裡面設定 "%+數字+指定器" //被替換項目 %(+數字) //指定替換項目


#print("|%-10d|"%(123))
在指定器%10d 內加入負號 可以向左對

#print("%10d%10d%10.f"%(1,2,3))
#多項指定器用法

#print("{0:5d},{p:4.1f}".format(1234,p=123.11))
#指定key,word 寫法 起始為0項 或字母=來使用

for b in range(0,101):
#宣告變數b執行100變

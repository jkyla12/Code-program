# Code-program
print("hello")

changme=str(input("Please set up your password"))

x=0

password=str(input("type password here"))

if password==changme:
             print("password accepted")
else:
             while password!=changme:
                 if x<4:
                     print("wrong input try one more time")
                     print(x+1,"attempt")
                     x+=1
                     password=str(input("try one more time"))

                 else:
                    print("Access denied")

                    break

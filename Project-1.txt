def person(**data):
    #print(data)
    for k,v in data.items():
        if k == 'firstname':
            print(k, ' :',v)
        elif k== 'lastname':
            print(k,  '  :', v)
        elif k == 'age':
            print(k,'       :', v)
        else:
            print(k, " :" , v)
    print(" ")
e=1
while e != '0':
    fname = input("enter first name: ")
    lname = input("enter last name: ")
    age = input("enter age: ")
    mobile = input("enter number: ")

    person(firstname=fname,lastname=lname,age=age, mobilenum=mobile)


# hackthon-1
hospital=[]
_detail=[]
_raree=[]
_rare=[]
print('Are you a Admin or User')
x=input('Enter :')
if(x== 'Admin'):
    n = int(input('Enter number of hospitals you want to add: '))
    for i in range (0,n):
     k = input('Enter name of hospitals you want to add:')
     _hospital.append(k)

elif(x== 'User'):
    y=input('Do you want to register or request or view as Admin:' )
    if(y== 'register'):
         v= int(input('How many peoples blood you want to register: '))
         for j in range (0,v):
             _name=input('Enter your name')
             _bloodtype=input('Enter your bloodtype:' )
             _mix= _name + _bloodtype
             _detail.append(_mix)
             continue
    elif(y== 'request'):
            _search=input('Which blood group are you looking for :')
            _type=input('Enter :')
            if(_search=='AB+'):
                 print(_name)
            if(_search=='AB-'):
                 print(_name)
            if(_search=='B+'):
                 print(_name)
            if(_search=='B-'):
                 print(_name)
            if(_search=='O+'):
                 print(_name)
            if(_search=='O-'):
                 print(_name)
b=input('R u looking for rare bloodgroup: ')
if(b=='yes'):
     q=input('Enter bloodgroup:')
     if(q=='AB+'):
        print(_name)
     if(q=='AB-'):
         print(_name)

    


 

if(x== 'Admin'):
    n = int(input('Enter number of hospitals u want to add: '))
    for i in range (0,n):
     k = input('Enter name of hospitals u want to add:')
     _hospital.append(k)
elif(x== 'User'):
    y=input('Do u want to register or request:' )
    if(y== 'register'):
         v= int(input('How many peoples blood u want to register: '))
         for j in range (0,v):
             _name=input('Enter your name')
             
             _bloodtype=input('Enter your bloodtype:' )
             _mix= _name + _bloodtype
             _detail.append(_mix)
             continue
                   
    elif(y== 'request'):
            _search=input('Which blood group are you looking for :')
            if(_search=='AB+'):
                 print(_name)
            if(_search=='AB-'):
                 print(_name)
            if(_search=='B+'):
                 print(_name)
            if(_search=='B-'):
                 print(_name)
            if(_search=='O+'):
                 print(_name)
            if(_search=='O-'):
                 print(_name)

t=input('Do you want to view data as admin:')
if(t=='yes'):
     print(_detail)
print(_hospital)



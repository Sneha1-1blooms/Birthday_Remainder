# Birthday_Remainder
dict={}
feed={}
while 1:
    print('************BIRTHDAY APP************')
    print('1. Show Birthdates')
    print('2. Add to birthday list')
    print('3. Exit')
    choice = int(input('Enter the choice'))
    if choice==1:
        if len(dict.keys())==0:
            print('Nothing to show')
        else:
            name=input('Enter the name for birthday')
            birthday=dict.get(name ,'no data found')
            print(birthday)
    elif choice==2:
        name=input('Enter name to add')
        date=input('Enter date')
        dict[name]=date
        print('Birthday Added')
    elif choice==3:
        print('Thnk uh for using my software!!!!!')
        print('Kindly give ur feedback too! : 1: bad 2: good 3:Excellent')
        feedback=int(input())
        feed=feedback
        print('Thnks for ur feedback')
        print(feed)
        break
    else:
        print('Please choose valid option')
    

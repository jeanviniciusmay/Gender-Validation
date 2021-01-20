# Jean-May
Gender Validation 

gender = str(input('What is your gender? [M/F/U] \nM - Male\nF - Female\nU - Undefined\n ')).upper().strip()
while gender != 'M' and gender != 'U' and gender != 'F':
    gender = str(input('\033[31mYou typed incorrectly!\033[m\n\033[33mRetype the letter equivalent to your gender:'
                       '\033[m [M/F/U] \nM - Male\nF - Female\nU - Undefined\n ')).upper().strip()


if gender == 'M':
    print('Your gender is \033[34mMALE!')
elif gender == 'F':
    print('Your gender is \033[35mFEMALE!')
else:
    print('Your gender is \033[33mUNDEFINED!')

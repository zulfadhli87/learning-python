# learning-python
basic python 
Currently doing the course "Introduction to Python: Fundamental" by Microsoft. Most of python flow and mini project in this repo are based from the course.

# [ ] Get user input for first_name
# [ ] iterate through letters in first_name 
#    - print each letter on a new line

first_name = input ("please type your name :")
new_name = " "
for i in first_name:
    if i.lower() == "i":
        new_name += i.upper()
    elif i.lower() == "o":
        new_name += i.upper()
    else:
        new_name+=i
        
print (new_name)

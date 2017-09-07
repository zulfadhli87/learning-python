# learning-python
basic python 
Currently doing the course "Introduction to Python: Fundamental" by Microsoft. Most of python flow and mini project in this repo are based from the course.

Program: Mystery Name
get user input for first_name
create an empty string variable: new_name
iterate through letters in first_name Backwards
add each letter to new_name as you iterate
Replace the letter if "e", "t" or "a" with "?" (hint: if, elif, elif, else)
print new_name
example: "Alton" = "no?l?"
--------------------------------------------------------------------------------------------------------------------------------------
# [ ] Create Mystery Name
first_name = input ("please type your first name ")
new_name = ""
for i in first_name[::-1]:
    if i =="e":
        i = i.replace("e","?")
        new_name += i
    elif i == "t":
        i = i.replace("t","?")
        new_name += i
    elif i == "a":
        i = i.replace("a","?")
        new_name += i
    else:
        new_name += i

print (new_name)
print (first_name)
-----------------------------------------------------------------------------------------------------------------------------------

#took way too long to solve this problem. Initially i use "i.replace("t","?")" to replace character in string to "?". Turns out that string.replace() returns the string with the replaced values. It doesn't modify the original so I have to modify the replace function like this " i = i.replace("t","?")"

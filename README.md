# learning-python
basic python 
Currently doing the course "Introduction to Python: Fundamental" by Microsoft. Most of python flow and mini project in this repo are based from the course.


##  Program: print each word in a quote


quote = "they stumble who run fast"
start = 0
space_index = quote.find(" ")
while space_index != -1:
    print ("index for 'space' is : " + str(space_index))
    y = int(space_index)
    space_index = quote.find(" ", space_index +1)
    print ('this is start ' + str(start))
    print('this is y ' + str(y))
    print('"' + quote[start:y] + '"', "\n")
    start = 0 + y 
    
    
    ## this code is too complex i think. Maybe can simplify by a lot by using function that i have nnot learnt yet.

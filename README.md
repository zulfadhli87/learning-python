Program: Words after "G"/"g"¶
Create a program inputs a phrase (like a famous quotation) and prints all of the words that start with h-z
Sample input:
enter a 1 sentence quote, non-alpha separate words: Wheresoever you go, go with all your heart
Sample output:
WHERESOEVER
YOU
WITH
YOUR
HEART
split the words by building a placeholder variable: word
loop each character in the input string
check if character is a letter
add a letter to word each loop until a non-alpha char is encountered
if character is alpha
add character to word
non-alpha detected (space, punctuation, digit,...) defines the end of a word and goes to else
else
check if word is greater than "g" alphabetically
print word
set word = empty string
or else
set word = empty string and build the next word
Hint: use .lower()
-----------------------------------------------------------------------------------------------------------------------------------------

# [] create words after "G"
# sample quote "Wheresoever you go, go with all your heart" ~ Confucius (551 BC - 479 BC)
alpha = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p","q","r","s","t","u","v","w","x","y","z"]
#alpha_upper = [i.upper() for i in alpha]
#print (alpha_upper)

word = ""
print ("index for the letter 'g' is : " + str(alpha.index("g")))
print ("index for the letter 'z' is : " + str(alpha.index("z")))

quote = input("please type a quote :")
x = quote.lower()
print (x)
for i in x:
    if i in alpha[6:26]:
        word += i
    else:
        print (i)
print ("the word is : " + word)

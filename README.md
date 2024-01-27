# python_split-
import string
print("\n\n----program 8(b)----\n\n")
my_str=input("Enter a string:")
words=my_str.split("!")
words.sort()
#display the sorted words
for word in words:
  print(word)

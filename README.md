# 1.Program

**WAP to find the roots of a quadratic equation:**

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/8725a437d9cbe2bac948ba267e12f65c12a19a12/tempImage3MWTR6-0000.jpg)

# 2.Program

**WAP to accept a number ofber "n" to compute the following:

A. Check if "m" is prime or not.

![image](

B. Generate all prime number till "n".

![image alt](

C. Generate first "n" prime number.

![image alt](

D. Calculate sum of first "n" natural numbers

![image alt](

# 3.Program

** WAP to create a pyramid of the character "*" and a reverse pyramid.

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/213fe67d574a6fc4b4d9a10334e19765a00abc39/tempImageaRBEJ5-0000.jpg)

# 4.Program

** WAP that accepts a character and performs the following:

a. print whether the character is a letter or numeric digit or a special character.

b. if the character is a letter, print whether the letter is uppercase or lowercase.

c. if the character is a numeric digit, prints its name in text

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/6ab3cc7313d3ca206d6d080c4f9ddb20497dcdf6/program%204.jpg)

# 5.Program

*WAP to perform the following operations on a string.**

1.find the frequecy of a character in a string.

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/6c46e1eb8f59ab2a7cb654b2aa29170572212453/PROGRAM%206.png)

2.Replace a character  by another character in a string.

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/de04e001e7310dd31ac82ce54b6c2e83ae664781/5.2.jpg)

3.Remove the first occurance of a character in a string.

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/3e6668f45dc0ab7b5782e10533bda98507ed2357/PROGRAM5.png)

4.Remove the all occurance of a character from a string.

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/f671c67e48dfde1881c9d40e8f7c89c34aec9435/PROGRAM%204.png)

# 6.Progarm

**WAP to swap the first n characters of two strings.**

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/4bbaaa14bfa89a3940a65a151881ff6d5c45a44e/PROGRAM%203.png)

# 7.Program

**write a function that accepts two string and returns the indices of all the occurences of the second string in the first string as a list.If the second string is not present in present in first string then it should return -1.**

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/fc4af0ef828c04de02e9013010007d25e1c0f16b/PROGRAM3%202.png)

# 8.Progaram

**WAP to create a list of only the even integers appearing in the input list(may have elements of other types) using for loop and list comprehension.**

![image alt](https://github.com/Gautam-io-dev/python_programs/blob/f2856764d0c53939b526d6984a7e642060c262c9/PROGRAM1.png)

# 9.Program

**WAP to read a file and**

(i) Print the total number of characters, words and lines in the file.

    filename=input("Enter filename:")
    file=open(filename, 'r') 
    lines = file.readlines()
    num_lines = len(lines)
    num_words = sum(len(line.split()) for line in lines)
    num_chars = sum(len(line) for line in lines)
    print(num_chars, num_words, num_lines)

(ii) Calculate the frequency of each character in the file. Use a variable of dictionary type to maintain the count.

    def character_frequency_in_file(filename):
    freq = {}
    with open(filename, 'r') as file:
        text = file.read()
        for char in text:
            freq[char] = freq.get(char, 0) + 1
    print(freq)

    character_frequency_in_file("sample.txt")

(iii) Print the words in reverse order.

    def reverse_words_in_file(filename):
    with open(filename, 'r') as file:
        words = file.read().split()
    print(' '.join(reversed(words)))

    reverse_words_in_file("sample.txt")







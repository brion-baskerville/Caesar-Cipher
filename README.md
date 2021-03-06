# Caesar-Cipher

The goal: Use a Caesar Cipher to mask the given plaintext user input by using the given user shift value. The problem: How should the data be held? The data needs to be separated, each character needs to be shifted by the shift value, and then printed back out in the same position. 

To tackle the problem, I received the input, assumed to only contain lowercase letters and spaces, via a Scanner, input.nextLine, making it a String. I also receive the shift value from the user, assumed to be positive numbers. I then convert the String into a character array by using .toCharArray(). The plaintext has now been separated into characters. I shift the characters by the shift value, and place them back in their correct positions in the character array. Once every value has been shifted I then converted the character array to a string by creating a new string object, new String(), and print out the ciphered string.

# Lessons Learned
Something that I learned that I was really excited about was the “new String(A)” for making character array A into a String. I had originally had my program print out the values in a for loop, but as I read over the instructions again I noticed I could just return the character array as a String. This makes it so that I do not need the for loop, and makes the code much simpler, and cleaner.

I believe the Caesar Cipher is not a good method of encryption. To be able to crack the cipher all you would need is the shift value, and then there goes the US missile launch codes that were hidden behind the cipher.

# Introduction to Variables: Strings - Lab]
# My Friend Did this
## Introduction
Okay, we have learned about our first data type, the String! Now let's do a little practice with strings. We'll use the methods and functions we introduced in the previous lesson to flex our string-manipulating muscles!

## Objectives

You will be able to:

* Apply string methods to make changes to a string
* Use concatenation to combine strings

## Instructions

Follow the steps below to manipulate the strings and assign the values to the variables below.

**1.** Below, we have a sentence whose cases are all over the place. Let's normalize the cases and make everything lower case except the first letter in the sentence. **hint:** *there is a string method that does this*


```python
sentence = "woW WE LOVE cOdInG and strINGS!"
sentence
```

**2.** Next, we have our Flatiron mantra, but it's not in title case like it should be! Let's fix that and use another string method that makes all strings first letter capitalized. 


```python
flatiron_mantra = "learn. love. code."
flatiron_mantra
```

**3.** The next thing we want to do is practice turning other data types into strings. Below, we have a number `1234`, which happens to be our street number in our address, which is a string. So, let's turn the number into a string so we can eventually add it to our address. The process of linking different strings together is called **concatenation**. 


```python
num_to_string = 1234
num_to_string
```

**4.** Let's take the `num_to_string` and add it to the beginning of our street address below. We need to concatenate the variable to the beginning of our string so that we have our full address all in one string and assigned to the variable `full_address`. **hint:** `None` *is a placeholder in the below code for you to edit*


```python
full_address = None + " Abc street, Hometown USA"
full_address
```

**5.** Finally, let's replace some of the characters in a string. Let's say Bart is upset with his family and wants to be adopted by the Flanders family. How would you replace his last name?

**Hint:** We did not directly cover this method in the lesson. Check out the string helper docstring for a list of available methods. 


```python
help(str)
```


```python
name = "Bart Simpson"
name = #Your code here; update the variable name
```

## Summary
Great work! In this lab we practiced our skills with strings. We can now manipulate, coerce, and concatenate strings. Remember if there are any things you can't remember or want to discover about code that isn't mentioned in this material, googling is always a great practice!

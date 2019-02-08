---
layout: post
title:      "Data Structures"
date:       2019-02-08 02:27:02 +0000
permalink:  data_structures
---


**Strings**

* Strings are a series of characters contained within either single or double quotation marks. Strings can be called either literally or using the class constructor. Creating a string using the literal construction entails typing the phrase within quotes, such as "Hello World!" Creating a string using the class constructor, however, calls the function string.new to create a new string. For example, calling string.new("Hello World!") will also return the string "Hello World!". 
* Strings can also be interpolated using given data. Let's say we wanted to say hello to our group of friends: Julia, Jane and Jeanine. We could type out the greeting for each person, but to make it easier, we 

**Booleans**

* Booleans return either true or false depending on the evaluation of a given statement. For example, the evaluation of 10 == 10 will return true but the evaluation of 20 == 10 will return false. We would describe these evaluations as either truthy or falsey to describe the state of being either true or false. 
* Most data types will return as true, however both false and nil will return falsey. 

**Numbers**

* Numbers fall into two different categories: fixnums and floats. Fixnums are integers or whole numbers. Floats, however, are decimals. These numbers function the same as basic arithmetic. For instance, adding 0.5 and 0.5 will still return 1 and 2 + 2 will still equal 4. The most notable difference, really, will be in the notation of the response if performing any mathematical operations on a combination of fixnums and floats. Let's say we're multiplying 2.25 and 4. Reasonably, we know this equals 9, however, since one of the numbers is a float with a decimal point, the result will actually be 9.0. 

**Arrays**

* Arrays are lists consisting of strings or numbers. While it's possible to have an array that has a mixture of strings and numbers, it's not a great idea. Arrays can be created either literally or using the class constructor. Creating an array literally entails declaring values within square brackets, such as array = [1, 2, 3, 4, 5]. The array previously declared contains five fixnum values. The class constructor can create the same array, but we would call the array constructor to do so: Array.new.

**Hashes**

* Hashes are much like dictionaries, in that they are a series of key-value pairs. They're great for keeping track of something like a report card. Instead of having just listing out all of the items necessary to make up a report card, you can categorize everything to make it easier to find. Let's say we have a student, Brian Smith, who is in 12th grade, is valedictorian and is class president. Using hashes, we can assign all of these attributes to Brian Smith, thereby making it easier to access later. 

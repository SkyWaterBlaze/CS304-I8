# CS304-I8

## Introduction
In this lab, students were asked to see if they could complete a piece of pre-existing, incomplete Java code by inserting it into it. To accomplish this, an extension was to be added to the end of the existing code, which would output the data the code interpreted into readable text and present it to the user via the console. The pre-existing code produced row objects to house the data, opened an input file with a specified name, and generated keys from the top row (header) to split into an ArrayList. After reading and processing the data of/in each row, the pre-existing code would print the total number of rows read from the given input file and close the file. Under Dr. Ogden's supervision, this lab was carried out in the Computer Programming II course (CS232).

## Methodology
The NetBeans software was the only piece of hardware needed to finish this lab. The first goal of the user-inserted/created code was to find a way to turn the data the code was reading from the rows (source: provided input file) into data that the user could read and understand. The currentRowData variable's current contents were updated using a hashmap after a numeric data limit of 5 was first established and set. Next, a print function was developed to output the variables firstName, midInit, lastName, streetAddr, city, state, and zipCode that had previously been input. FirstName, midInit, and lastName were combined in one row, followed by streetAddr in its own row, and city, state, and zipCode in the final row. In order to ensure that exceptions would be output as errors and be simple to read so that any subsequent mistakes could be corrected, a catch function was lastly added.

## Results
The outcome was positive, and everything ultimately functioned as intended. Once I understood the concept of what I was supposed to do, the lab was fairly easy. After much research and trial-and-error, I was finally able to use HashMaps correctly in the lab. I had initially struggled to understand them and how to use them.

## Conclusion
I was tasked with taking the lab 4 Java file and adding my own code to it so that it would properly function as it was supposed to. I initially had trouble getting some of the concepts in the code to work properly, but I was eventually able to get past the difficulties and write the code required to finish the lab with little to no errors. I now have a better understanding of what HashMaps do and how they fit into the overall Java programming ecosystem thanks to this assignment.

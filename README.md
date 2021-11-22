# Convert Text-to Handwriting Using Python

In this project we'll use python library that's "pywhatkit"  for converting text to handwriting. this small project you will know how python convert text to handwriting in image format.

## Explanation
  - Install Python Library using Cammand Promt `pip install pywhatkit` or  [Download](https://pypi.org/project/pywhatkit/)
  - Import the Module using import keyword 
  - Initilizing the text using variable, also you can add text via user input and pdf file format.
  - Using pywhatkit function that is `text_to_handwriting()`
  - Passing three parameter inside the function
   1. Text file 
   2. Handwritten text image file format
   3. Text Color in RGB format
   
   -  Example: `pw.text_to_handwriting(txt,"img1.png",[0,0,138])`
   
   NOTE: If you Don't pass the image file format & text color  `pywhatkit` default name & color save.
   

## Demo
<img src="text_to_handwrting.png">

## Soruce Code
- [Download](https://drive.google.com/file/d/1cWIfTZ-t6TQ0CRCmrALZ-loa21YqEdJO/view?usp=sharing)


# Contribution Guidelines

If you have got an optimized solution to a problem or, lets say, the existing solution is failing on some test cases and you got a working solution, then there is really a high chance of getting you pull request being accepted. 
**Note:** If you have got an optimised solution, but the existing solution is also working, then:
1. Make another file in the corresponding folder'
2. Name it `<problem name in snake case>-<your name in snake case>-Optimized.cpp`.
3. Generate a pull request and wait.

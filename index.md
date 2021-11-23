
# Convert Text-to Handwriting Using Python

## Description
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

## Code 

```python
# Author: Abdul Raza
# Version: 0.1
# Date: 22th November 2021

import pywhatkit as pw
txt =""" What is Lorem Ipsum?
Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
when an unknown printer took a galley of type and scrambled it to make a type specimen book. 
It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. 
It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, 
and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. """
 
# pw.text_to_handwriting(txt,"img1.png",[0,0,138])
pw.text_to_handwriting(txt)
print("END")

```

## Soruce Code
- [Download](https://drive.google.com/file/d/1cWIfTZ-t6TQ0CRCmrALZ-loa21YqEdJO/view?usp=sharing)



### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

#### Author: Abdul Raza



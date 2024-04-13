# drawing_dots
It's about the hirst spot painting. we going to recreate it with the help of coding in python.
Painting called "Antipyrylazo III" (signed 'D Hirst' on the reverse household gloss on canvas. (estimated Euro of 9,00,000 - 12,00,00) sold out for Euro 12,75,000.
For the main code we will be using 2 libraries Turtle() and Colorgram().

Colorgram is python library that lets you extract colors from images. Compared to other libraries, the colorgram algorithm's results are more intense.

pip install colorgram.py ---->package

* Below is the example of executing the colorgram 
  
code:-

import colorgram

rgb_colors = []
colors = colorgram.extract('image.jpg', 30)
for color in colors:
    r = color.rgb.r
    g = color.rgb.g
    b = color.rgb.b
    new_color = (r, g, b)
    rgb_colors.append(new_color)

print(rgb_colors)

(NOTE:- for running the code you need a image. make sure the image.jpg and code.py are on same folder)

result - rgb = [(245, 243, 238), (246, 242, 244), (202, 164, 110), (240, 245, 241), (236, 239, 243), (149, 75, 50),
       (222, 201, 136), (53, 93, 123), (170, 154, 41), (138, 31, 20), (134, 163, 184), (197, 92, 73), (47, 121, 86),
       (73, 43, 35), (145, 178, 149), (14, 98, 70), (232, 176, 165), (160, 142, 158), (54, 45, 50), (101, 75, 77),
       (183, 205, 171), (36, 60, 74), (19, 86, 89), (82, 148, 129), (147, 17, 19), (27, 68, 102), (12, 70, 64),
       (107, 127, 153), (176, 192, 208), (168, 99, 102)]

       

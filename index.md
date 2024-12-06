---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---
 
Welcome!, my name is Damian Dobrzycki. I'm a 3rd year in ATU doing Software and Electrical Engineering course. This is my VGA Project, its going to have 3 types of different flags, Ireland, France and Belgium.

## **Template VGA Design**

### **Project Set-Up**
Summarise the project set-up and design flow. Include a screenshot of your own set-up, for example see the image of my Project Summary window below. Guideline 1 short paragraph.
The Project will generate the flag of Ireland below is my Project Summary.

![image](https://github.com/user-attachments/assets/82107fde-8955-4431-b028-7da50b1b285a)


### **Template Code**
The Structure and design of the Verilog code that we were giving were to generate a Colour Cycle and what we had to do was to change the code from Colour Cycle to Colour Stripes so that the code generates a certain amount of colour for example Black, Red, Blue, Orange, Yellow, Pink and Cyan. What we had to do was to change it into something that we want to change it too, I changed it to the flag of Ireland

### **Simulation**
So what the simulation does is that it generates a bitstream which then transports that code into the VGA Board and then into the VGA Port which an image will show on the screen.

### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.

### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).

### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.
What I changed in the code was that I changed the distance between each Stripes from 0 - 220 was the first colour 220-240 was the second colour and so one to make the Irish flag.
I implemented that code 5 times so that it displays the flag of Ireland on the VGA

![image](https://github.com/DamianDobrzycki1/VGA-Project/blob/main/docs/assets/images/Screenshot%202024-12-02%20155133.png)

### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.
### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">

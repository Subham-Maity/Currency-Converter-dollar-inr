# Intro
I am **Subham Maity**
I love Programming. One of the aims I had when I started ```CodeXam``` was to make learning programming easy.
## Help us improve this guide - **Fork, Pull Requests, Shares and Likes are recommended**!
# [**For Reference You can Follow This Video For Step By Step**](https://youtu.be/PWKzYFX5_As)
![screenshot](https://github.com/Subham-Maity/Java-Swing-GUI-Based-Projects/blob/master/Java%20Currency%20Converter%20%20(dollar-inr)/Screenshot.png)

# Java program to convert Currency using AWT
Difficulty Level : Easy
Last Updated : 08 May, 2020
Swing is a part of the JFC (Java Foundation Classes). Building Graphical User Interface in Java requires the use of Swings. Swing Framework contains a large set of components which allow a high level of customization and provide rich functionalities, and is used to create window-based applications. Java swing components are lightweight, platform-independent, provide powerful components like tables, scroll panels, buttons, list, colour chooser, etc.

In this article, we’ll see how to make a currency converter which includes conversion between INR and Dollar. Two text fields are implemented with the labels Rupees and Dollar.

Note: It is assumed that 1 dollar is equal to 65.25 rupees.

Examples:

Input: INR = 130.5
Output: 2.0
Explanation:
One dollar is 65.25 rupees. So, 130.5 rupees is two dollars.

Input: Dollar = 4.5
Output: 293.625

Approach: To solve this problem, the following steps are followed:

**1.First, we need to create a frame using JFrame.**

**2.Then, create two labels, two textfields and three buttons(the first button for rupees and the second button is for the dollar) using JLabel, JTextField and JButton.**

**3.Name these components accordingly and set their bounds.**

**4.Now, in order to perform the conversion on button click, we need to add Event Handlers. In this case, we will add ActionListener to perform an action method known as actionPerformed in which first we need to get the values from the text fields which is default as a “string”.**

**5.So, in order to perform mathematical operations, we need to convert them into double data type using Double.parseDouble(Object.getText()) and again converting from double to string to place the final value in the other text field using String.valueOf(object).**

**6.Finally, for changing the values, we use Object.setText(object), the second object is for selecting which field we want to replace.**

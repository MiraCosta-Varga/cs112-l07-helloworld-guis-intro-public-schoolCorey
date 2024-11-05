[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=16960735)
![java fx logo](https://imgur.com/pyTZgzk.jpg)

# Lab 07: HelloWorld + GUIs Intro

GUIs, or Graphical User Interfaces, are the most common way we use computer applications. Whether the input is from the
keyboard, mouse, or touch, there are many ways users interact with GUIs to accomplish tasks or solve problems. As a
front-end developer, a programmer who focuses on the side that the user interacts with, we must constantly think of our
end-users and how to best support them in accomplishing their task. For that, we're going to have to practice some
fundamentals of GUI development through learning the JavaFX library.

## Tips

- Use OLI to understand how the given Hello World functions and other examples
- Search for generic things you want to accomplish, like "change title of javafx window" to give you some direction
- All parts below require very little code. Each ToDo can be as simple as changing a line of code or adding 2-3 lines
  max. You don't need to mess with the structure of the program, just editing little pieces

## To-Dos

0. Setup IntelliJ (BIG Step! follow instructions on Canvas)
1. Clone project
2. Change the code so that it prints "Hello CS112" to the console when the button is pressed
3. Change the windows title to your group number and name
4. Change the code so that when the button is pressed, the `Label` element says `Hi #i, User!` where `i` is the actual #
   of times the button has been pressed.
5. Add a [TextField](https://docs.oracle.com/javase/8/javafx/api/javafx/scene/control/TextField.html) element to the GUI
   for a user to type in their name.
   - Update the button so the `Label` element now includes the users name. For example, if it's `Miles` 3rd time of
   clicking the button, it would say `Hi #3, Miles!`

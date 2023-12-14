In this project I created a color converter. The three files provide a simple implementation of a color converter (CSS named colors, RGB values, hex-representation).
Given a text file of color names and RGB components. The user can input a specific RGB component and the program returns the name, hexvalue, and the RGB component
of the color. 
Color Class: provides 3 different representation of a color which are name, hexvalue, and RGB componenets. 
ColorList Class: provides a storage for multiple color objects. 
ColorConverter Class: provides the main method where users can interact with the project. File name with list of colors must be given as command line argument. 
Then we create the list of color objects from the text file. Then we start the user interaction where a user can input an RGB component for any color and if valid 
we return the name, hexvalue, and RGB component of the color else we give a error message to let the user know the input isn't valid. 

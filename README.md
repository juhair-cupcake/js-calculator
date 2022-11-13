# pussyHunterCalculator

A calculator for New JS Coders. Made with HTML, CSS & Javascript.

# link for live view

### [Click_Me](https://juhair-cupcake.github.io/js-calculator/)

![ScreenShort](https://github.com/juhair-cupcake/js-calculator/blob/master/asset/Capture.png)

# Know the code

1. **lastResult** uses for containig the real result or the output result

1. **buffer** uses for showing the user their inputs

1. **numbers** use for collecting temporary data from input's

1. **command** is for storing calculation type, 1 = +, 2 = -, 3 = \*, 4 = /.

1. **point** is for if we use float number as input and the position of that point value.

1. **pressed(Equel/Command)** is use for knowing that is user is pressing that button or not...!

   - After getting the result if user pressed any command(+,-,\*,/) then the new result will the modified result of the old result. exmp: 5 + 5 = 10 + 5 = 15 Otherwise the old result will be deleted. //pressedEquel is the reason for doing this.//

   - If user pressed more than one conmmand(+,-,\*,/) the only the first command will be taken others will be ignored. //pressedCommand is the reason for doing this.//

1. **.toFixed()** function is used for limiting the output numbers after decimal.

1. **executeCommand()** do all the calculations. \_\_\_\_Opperation use for tracking the command that need to execute.

1. **addNumber()** is made for taking input data. If the input is a decimal number it will multiply the old number with 10 then add them. exmp: buffer = 12, input = 5 [ (buffer x 10)+input ] = (12 x 10)+5 = 125. if the buffer is already empty then it just add the input istade of mulpication. Float number will be added as [ buffer + input/(10 x floatPosition) ].

1. ID is used for uniquely know the button, so JS can manupulate the result as user want.

It's free, and thats a great price.👌

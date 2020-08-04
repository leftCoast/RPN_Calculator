***This is a really old version. The actual calculating part should be fine, but the UI stuff is really out of date. I would be surprised if it compiled at all on the newer IDEs. There are updated version(s) of this, if you really want to try building it. Drop me a note and I can help set you up with one.***

This is the code for creating the Left Coast RPN calculator.  If you’re reading this, I’d assume you have built or are building one of these.

A link : http://www.leftcoast.biz/iWeb/Left_Coast/The_calculator.html

First step : Get your touchscreen to work on your standard Arduino with Adafruit’s demo. stuff. Just like it’s supposed to work. This will be between you and the Adafruit folks. Its a big enough nut to crack in itself. And, you’ll learn a lot.

Second Step : Get the Teensy stuff installed and be able to run the “blink” sketch from the IDE. Yet another learning curve. This will be between you and the Teensy people.

Third step : Wire the Teensy into the touchscreen. Its not supposed to be wired to a Teensy, so there’s a trick to it. Notice the header pins? They are not through hole pins. But, they do have handy little feet sticking out. One each so that you can, if your careful, solder your wires to the feet.

Fourth step : Get the Adafruit demo code running on the touchscreen from your Teensy. You will need to set the clock speed to 78. You don’t want the “over-clock” default selection. Its a menu item on the IDE.

Last step : Notice I saved our stuff ‘till last? This is because there are so many learning curves one must overcome to get all these things to work together. Each step has its “owner”.  The owners of each step are the ones to help out. Meaning, if you make it this far, you’ll be WAY easier to help, because you’ll be educated on all the foundation steps. And, it’ll just be our stuff that’s the trouble.

So download this code, drop the HP_Calc folder into your Arduino folder and the LC_RPNCalculator, LC_Screen, LE_baseTools folders into your Arduino libraries folder. 

Open up HP_Calc.ino, compile for Teensy and you should be good to go.

Good luck

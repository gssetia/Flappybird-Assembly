# Flappybird-Assembly

## Navigation 
<a name="top"></a> 
1. [Overview](#description) 
2. [How to Install](#install) 
3. [How to Play](#play) 
6. [License](#license)

## Description 
<a name="description"></a>
Have you ever played Flappy Bird on your mobile device but felt it was missing something?
Maybe you wanted a more low level experience that brings you away from the flashy and advertisement ridden Flappy Bird of the modern ages. 
Well then Flappy Bird made using assemby is right for you!

## How to Install 
<a name="install"></a>
First you need to install the software that can run assembly. 
Go to this link and press 'Download Mars' to download Mars V4.5 for free. 
http://courses.missouristate.edu/kenvollmar/mars/download.htm

Now start up mars and go to File -> Open and select flappybird.s.
To get the game started, you must execute the assembly code by pressing the ![execute](https://user-images.githubusercontent.com/38819226/88502333-1a38cf80-cf9c-11ea-80ce-656b1b86da2c.PNG) button.

Now we need to setup the interface to interact with the game. 

For the display, go to Tools and press Bitmap Display. Alter the settings to fit the requirements of the game. 
![bitmap](https://user-images.githubusercontent.com/38819226/88502723-69333480-cf9d-11ea-929e-bc6f8f693432.PNG)

__It should look exactly like this.__

Next we need the controller to allow you to flap your wings. Go to Tools and press Keyboard and Display MMIO Simulator. We can use the bottom space to control the bird. The top space is not used. 

Finally, press the Connect to MIPS button on the Bitmap Display and the Keyboard Simulator. 

You are now all set to play Flappy Bird that is completely made using Assembly. 


## How to Play
<a name="play"></a>

The idea of this game is to flap your wings and carefully fly between the green pipes. If any part of the bird touches the pipe then its game over. 
To start the game, press the ![start](https://user-images.githubusercontent.com/38819226/88503119-bf54a780-cf9e-11ea-8f4f-2be86dbb290d.PNG) button. 
Go to the bottom space of the Keyboard Simulator and keep typing f to flap your wings.
If you lose, then press the ![reset](https://user-images.githubusercontent.com/38819226/88503247-1a869a00-cf9f-11ea-8e32-20015e42a79e.PNG) button to reset the game. Just press the start button again to start.

Eventually, the pipes became faster and faster so be sure to sharpen your reflexes. 

![flappy](https://user-images.githubusercontent.com/38819226/88503333-69343400-cf9f-11ea-8ab3-bd79adfd6afc.PNG)



## <a name="license"></a>License Information

The MIT License (MIT)

Copyright © 2019

You can find a copy of the License at https://mit-license.org/

License for them is in `Public Domain`


[Back to top](#top)

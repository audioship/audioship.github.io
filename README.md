Joshua Fields • joshuafields2019@u.northwestern.edu • EECS 397: Digital Musical Instrument Design • Northwestern University • Prof. Stephan Moore

## Using the Instrument

### Who is the expected user? 
The expected users of this instrument are anyone who wants to put their listening skills to the test. It's designed such that the performers do not need to have any prior experience, just the ability to listen and make out the opposing players frequencies of ships.

### Expected use case
The expected use case is in staged performance setting. The two players are to sit on the stage facing away from a screen that is behind them, with the audience sitting in front of them. Thereby, the players are actively playing the game, while the audience is listening to the emergent sound scape as well as being able to track the progress of the game over the screen behind the player.


### How is the instrument played? What kinds of sounds are produced?
The instrument is played using two buttons and a knob. The darker button on each of the instruments fires a shot at the opponent. If the frequency of this shot matches the frequency of any of the opposing player's ships, that ship will be destroyed. The knob changes the frequency of your active ship, which you can utilize to match the frequencies that you hear coming from the opposing player's ships. The lighter knob button on each of the instruments changes the active ship. Each player starts with four ships and can rotate through in shooting and changing frequencies.

The sounds that are produced are that of a space battle soundscape. There is ambient space sounds that play in the backdrop of the entire game. When the players shoot, a shot sound effect is made with whatever frequency has been indicated by the player. If a player hits an opposing player's ship, there will be an explosion sound effect to indicate it has been destroyed.

## Building the Instrument

### How is it built? What software and hardware are used?

I built this instrument using a Max MSP patch that interprets the input from from the six sensors, all of which are connected to an Arduino Uno. The six sensors were two buttons and one knob on each of the controllers. These sensors were mounted on two adding machines, one an old fashioned tax adding machine and one a newer, more streamlined adding machine. The wiring for the sensors on each of the controllers are snaked together with a significant amount of length to enable greater flexibility in how for apart each of the players are during the performance. 

## Lessons Learned

### What lessons did I learn from making this instrument? What might I improve on in future iterations?

The biggest lesson that I learned in the making of this instrument is that hardware is not as scary as i thought. With enough patience and smart use of resources, hardware that fulfills your vision can be achieved. At the start of this process, I had never sautered before, or even built a circuit, so to be able to get everything working the way I wanted was something that I was proud of. One big moment in this process was when I streamlined my wiring and circuitry. After I did this, my buttons weren't working regardless of what I was trying. I tried different Arduinos, different bread boards, new wires, new buttons, and new sautering - but none of that resolved the issue. It ended up being the my circuitry had been incorrect the whole time, but through that process, I really learned how to debug hardware issues and to systematically go through all the possible issues that could be going on.

I also learned a lot of Max MSP throughout this process that I had no idea about before. Through this instrument, I feel I learned a lot about how I prefer to program in Max (which if you are curious is with lots and lots of subpatches and color coding) and how to think like a Max programmer. It was a lot of fun taking my sound ideas and figuring out the best ways to program them. Especially since Max is not really meant to design games, I enjoyed determining how to best store information in a way that made the game playable and took advantage of what Max does naturally.

In future iterations, I would like to change the shooting sample to be something that changes more directly in relation to the frequency, as at times it can be somewhat convoluted. I would also change how the knobs are implemented so the adjustments that are made to the frequency are centered around what the frequency was at before rather than just the frequency jumping to whatever the knob position indicates. I would also love to add some more interactables (such as asteroids) that will interact with the player shooting to add more depth to the generated sound scape. I would also love to more securely mount the sensors to the instrument so it doesn't feel as thrown together. 

## Pictures and Figures

![Controller 1](https://raw.githubusercontent.com/audioship/audioship.github.io/master/controller1.jpg)
![Controller 2](https://raw.githubusercontent.com/audioship/audioship.github.io/master/controller2.jpg)
![Display](https://raw.githubusercontent.com/audioship/audioship.github.io/master/displayScreen.PNG)

# Napkin Math
![image](https://user-images.githubusercontent.com/39680023/225874516-a06e5ed6-9f62-4b00-8da6-750f71967786.png)

## Formal Qualities
Designed to be viewed in a dark room, this installation measures approximately 7 feet high and 14
inches wide. The physical component of the installation consists of 38 napkins of various sizes with
numerous tally marks drawn on both sides. Although most of the tally marks are black, napkins with
red, blue, green, pink, and purple tally marks are scattered throughout the piece. Variations in
stroke thickness and size can be found throughout.
When a laser projector projects the digital component of the installation onto the sculpture in a very
dark room, the tally marks are completely obscured (they can be partially brought into view by using
a lamp-based projector and tuning the brightness). The rest of the room is partially illuminated by
the remainder of the projection and the reflection of the installation onto the walls. The projected
numbers change hue over time and softly vibrate based on the amplitude of the noise in the room
(the louder the volume, the more sudden the vibration, mimicking the effect of one being surprised
by a loud noise).
![image](https://user-images.githubusercontent.com/39680023/225875634-408ff342-85e1-41ea-aa61-f2146da5770e.png)


## Artistic Context

It was the careful and precise hand-made calculations done by predominantly black women that
sent Voyager to explore the solar system, wrote the C and C++ programs that launched the first
Mars rover and helped the U.S. put a man on the moon. Though rarely seen in the famous photos
of NASA’s mission control, these early human computers contributed immeasurably to the success
of the United States’ space program. The work that women - predominantly black women -
did for computer science didn’t just bolster the field; it also helped end world wars and pioneer
space exploration. The work they did was largely invisible, and they almost never got credit for their
work. In every case we know of, the “women’s work” was considered subordinate to the work of the
men for whom they computed.
This installation depicts this situation by projecting the programmed component onto the physical
calculations to obscure them from view, metaphorizing how women’s contributions were often
obscured from view and considered less valuable, even though theirs are a big reason why
humanity has made the technological leaps and bounds it has through the years.


## Code 

The code for this installation was created using p5.js for the client-side programming and node.js
for the server-side programming. The numbers depicted in the digital component of the artwork were generated through 
debugging statements inserted in code written by me or some of my students in January - March 2022. 

On setup, the server retrieves the output of the debugging
statements and sends them to the sketch. Upon reception, the sketch stores the
received numbers in an array and creates a selection of agents with them. These agents are
initialised at random positions with random hue values that change throughout the course of the
sketch. The size of the displayed number is a randomly generated value depending on the agent’s
location on the canvas. At each iteration of the draw loop, the x-coordinate of the agent is randomly
increased/decreased by an amount inversely proportional to the surrounding amplitude to mimic
the effect of being shaken.

## Video Demonstration 

https://www.youtube.com/watch?v=4NDDMNZzLic 

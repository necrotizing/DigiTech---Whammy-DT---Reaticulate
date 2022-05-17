# Whammy-DT---Reaticulate
This is my second experience ever regarding coding. If anything is done wrongly, then let me know and I'll dive into getting it right.

I think everything should be fine though, this is very basic stuff and works really well with my Digitech Whammy DT. 

Just need to remember to have the **ReaControlMIDI** plugin on the channel as well for it to be sent via MIDI to the pedal.

   ![Reaticulate - Whammy](https://user-images.githubusercontent.com/105749268/168903496-a39374f2-eef6-4e7e-a244-67a69074da75.png)

Here is how it looks along with the settings you'll need to set up in ReaControlMIDI. You actually just need to enable **Bank/Program Select** and **Control Change**.

   ![image](https://user-images.githubusercontent.com/105749268/168904012-70d40f3c-113d-48a7-afdc-c159698e8286.png)

And remember to route the outputs from the track you'll be using to trigger the program changes in the MIDI Hardware output section in the top right corner.

To view the program information in the midi editor you have to have to be viewing the **Bank/Program Select** in the Velocity/CC Lane.

   ![image](https://user-images.githubusercontent.com/105749268/168905117-2c56016a-1158-4cfd-b21b-5e6c00ddf6c1.png)

I know a very small number of people will actually use this but this would work exactly the same way to trigger Kemper/Quad Cortex/Axe Fx for a live set but probably using different program numbers. 

Highly recommend looking into Reaticulate, very interesting stuff, can't wait to deep dive into it with some sample libraries.

# entelect-challenge-2022
Just a very basic visualiser for the Entelect Challenge 2022

Using the Visualiser:
Open the HTML file in your browse, click the browse button top right (or below the players depending on screen size) and select the log file to replay.
Note: You have to disable compact logging by going to the appsettings.json file of the logger and setting "CondencedLoggingToggle":  "false"

As a last note Im not very high on Graphics Development. 
This is just a bare minimum to get me started with the real fun. 


Troubleshooting:
If nothing happens after selecting a file or you get an error in the developer console, try using firefox. If you still get an error in firefox... I don't know.

My Screen is 4K, so the map might be too large for your setup. 
In this case you might want to half all the variables for mapfactor as well as any ctx.rect

Example:
ctx.rect(outer+ix-10, outer+iy-10, 20, 20);

becomes:
ctx.rect(outer+ix-5, outer+iy-5, 10, 10);

I will probably handle scaling a little better later. 

If anyone has a better approach, feel free to reach out

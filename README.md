# entelect-challenge-2022
Just a very basic visualiser for the Entelect Challenge 2022

Using the Visualiser:
Copy any Match Replay file from the entelect challenge logger:
example: 
GameStateLog_2022-04-05_02-51-59_GameComplete.json

Rename the file to:
GameStateLog.json

If the visualiser.html file is in the same directory it will run the match, 
I will add some updates later if it is needed for my own development process (Like showing the state of scouting)

As a last note Im not very high on Graphicsl Development. 
Jus is just a bare minimum to get me started with the real fun. 


Troubleshooting:
My Screen is 4K, so the map might be too large for your setup. 
In this case you might want to half all the variables for mapfactor as well as any ctx.rect

Example:
ctx.rect(outer+ix-10, outer+iy-10, 20, 20);

becomes:
ctx.rect(outer+ix-5, outer+iy-5, 10, 10);

I will probably handle scaling a little better later. 

Lastly if you cannot run the visualiser and its caused by cors:
Create a chrome shortcut containing the --disable-web-security parameter at the end of the path. 

Cors has some known issues running localhosted files (Its because I am reading the gamestate JSON)

If anyone has a better approach, feel free to reach out

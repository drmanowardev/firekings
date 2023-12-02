# Fire Kings Test Hand Simulator

Are you trying to learn new ways to improve your Fire King strategy and deckbuilding? Look no further than this unique project I've been developing. This program is here to take your Fire King deck and simulate up to one million test hands in a matter of minutes and report back on the metrics behind each test hand as well as each step in the process. 

To get started, you will first need a Python compiler, which you can download at https://www.python.org/downloads/. When you run the installer, check the box that says "Add Python to PATH" and click "Install Now".

Next, you can download this repository as a zip file (or git clone for more advanced users), and make sure you extract all of the files together in the same folder.

You will find a file called "decklist.txt", which is pre-populated with a sample decklist. You can edit this file in a text editor to build your own decklist. You will need to follow the format of typing each card's name exactly how it is line by line. You will need to look at the file called "supported_cards_list.txt" to see which cards this program currently supports and for proper spelling. I hope to add more commonly used cards to this list in the future. Any non-engine cards, for example, "Skill Drain" and "Crossout Designator", that are not currently supported can be replaced with other non-engine cards that are supported such as "Infinite Impermenance" for the sake of getting the program to work properly.

Once that is all complete, you can run the "main.py" file using IDLE, a program which should come pre-installed with Python. You will be prompted with a few questions regarding simulation preferences. First, specify the number of test hands you want to simulate. Then, you will be asked if you want to see each step in the simulation. This is not recommended if you are simulating more than 10 test hands at a time, but you will generally want to enable this if you are unfamiliar with how Fire King combos work. Finally, the program will run and you will see your results. 

At the end of each simulation, there will be a small report on what percentages of common endboards your simulated test hands were able to end on, in order of worst to best.

As this program in still in development, if you encounter any hands that are not being played out optimally or properly, or if you have any questions, please ping DrManowar in the Fire Kings discord server.

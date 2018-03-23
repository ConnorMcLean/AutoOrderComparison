# AutoOrderCheck
Repository for a temporary project in assisting All American Auto parts to try and automate their Order to Delivery checking system.

Not many files inside, used python mostly within Anaconda and Jupyter, therefore lack of commits.

Project was to aid All American Auto Parts in automating the way they compare the order form with the delivery form. It was done by hand. so in attempt to increase efficiency i used python and its pandas data-frame library to compare both forms and look for discrepancies. 

Due to the nature of the delivery forms and differing part prefixes between suppliers a Master-sheet was required to allow for proper comparison, as details differed between the forms. The code converts the csv data files into data-frames, which it then compares to the master sheet and then to the delivery sheet, cataloging differences in a text file for later review. Project currently lacks a UI and is solely composed of a python code notebook.

The Repository also contains dummy data for test purposes.

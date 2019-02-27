###Enigma machine in python

This program will take an input text from a sender (Alice) and encrypt it, Bob has to choose the position of the three rotors between “A”, “B" and “C”. If the receiver (Bob) chooses the same options for the program, it will output the decrypted message. You can encrypt alphabetical characters, spaces, comas and dots.  

Each position of the rotor has has a dictionary of letters and symbols with a reference for another letter or symbol that it outputs, that output goes again through the second rotor with another set of dictionaries and again in the third. Then, it goes again through the process but viceversa to return the final result. 

When Bob sets the "machine" in the same mode it will follow the same path but the other way around giving you the message that Alice sent.
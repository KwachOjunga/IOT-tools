# gem_duino

Gem_duino is a tool that uses gemini api to automate the process of writing arduino sketches.

## Mechanics

The gem_duino is a cli tool written in both rust and python. A file containing its input text data is passed to it from which the prompt is extracted.
The file is currently general instructions that is parsed through by the app before it is passed to the gemini api.
For widespread application it should be able to access the GOOGLE_API_KEY saved in one's environment variables.

Its output is in the form of an ino file and a txt file that contains the explanation of what the sketch is supposed to do.

---
Ps : The name is still kinda lame.

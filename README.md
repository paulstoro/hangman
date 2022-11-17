# hangman
game Hangman(RUS) - Hangman is a classic paper and pencil game.
The idea of the gallows may be a little morbid, but it also adds to the excitement of the game, especially for boys.
Everyone wants to save the poor person from a grim fate!

## RUBY
this program was made with ruby, so u will need to open it on ruby

## HOW TO PLAY:
The computer is the executioner. He generate a random word from the file (**./data/words.txt**) and mark out blanks (short lines) for each letter of each word. 
Then you will guess a letter. If that letter is in the word(s) then the computer will write the letter in everywhere it would appear.
If the letter isn't in the word then a body part will be added to the gallows (head, neck, body, left arm, right arm, left leg, right leg).
You will continue guessing letters until you can either solve the word or all seven body parts are on the gallows.

## How to add words:
Too add words find the text file **./data/words.txt**, open it and add a word on a new line. 

## How to open the game:

```
git clone https://github.com/paulstoro/hangman.git
ruby main.rb
```

# _{Application Name}_

#### _{Brief description of application}, {Date of current version}_

#### By _**{List of contributors}**_

## Description

_The word to guess is represented by a row of dashes, representing each letter of the word. In most variants, proper nouns, such as names, places, and brands, are not allowed. Slang words, sometimes referred to as informal or shortened words, are also not allowed. If the guessing player suggests a letter which occurs in the word, the other player writes it in all its correct positions. If the suggested letter or number does not occur in the word, the other player draws one element of a hanged man stick figure as a tally mark.

The player guessing the word may, at any time, attempt to guess the whole word. If the word is correct, the game is over and the guesser wins. Otherwise, the other player may choose to penalize the guesser by adding an element to the diagram. On the other hand, if the other player makes enough incorrect guesses to allow his opponent to complete the diagram, the game is also over, this time with the guesser losing. However, the guesser can also win by guessing all the letters or numbers that appears in the word, thereby completing the word, before the diagram is completed. (wikipedia : https://en.wikipedia.org/wiki/Hangman_(game) as accessed 6/26/2017 at 11:26am _
## Specifications

| Rank  | Behavior  | Input  | Output |
|---|---|---|---|
|1| set target word from prompt  | "Donkey"  | var targetWord = "Donkey"  |
|2| prompt for user letter guess and push value to var  | "a"  | var guessLetters = ["a",]  |
|3| check for duplication of letter guess  |   "a" | "You have already guessed "a", pick another letter"  |
|4| compare letter guess to target word | "k" | "true"|
|5| find index of letter guess to targetWord | "k" | 3 |
|6| create empty word array of targetWord.length | "Donkey" | word = ["","","","","",""] |
|7| populate word array with correct guesses at correct index| "k" | word = ["","","","k","",""]


## Setup/Installation Requirements

* _This is a great place_
* _to list setup instructions_
* _in a simple_
* _easy-to-understand_
* _format_

_{Leave nothing to chance! You want it to be easy for potential users, employers and collaborators to run your app. Do I need to run a server? How should I set up my databases? Is there other code this app depends on?}_

## Known Bugs

_{Are there issues that have not yet been resolved that you want to let users know you know?  Outline any issues that would impact use of your application.  Share any workarounds that are in place. }_

## Support and contact details

_Please email {support} if you run into any issues or have questions, ideas or concerns.  We encourage you to contact us with suggestions or contributions to the code._

## Technologies Used

_{Tell me about the languages and tools you used to create this app. Assume that I know you probably used HTML and CSS. If you did something really cool using only HTML, point that out.}_

### License

*{Determine the license under which this application can be used.  See below for more details on licensing.}*

Copyright (c) 2017 **_{List of contributors or company name}_**

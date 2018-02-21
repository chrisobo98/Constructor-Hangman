# IMDB Top Movies CLI Hangman
Javascript game using constructor functions MySQL Amazon-like storefront using MySql workbench and CLI

### Prerequisites
```
npm install inquirer
  -https://www.npmjs.com/package/inquirer
```
Download the latest version of node

## Letter.js

- Used for each letter in the current word
- Each letter object displays an underscore
- Accepts a user's guess otherwise returns it false

## Word.js

- Contains word specific logic and data.
- Checks to see if any of the letters in the array match the user's guess and updates `foundLetter`
- Returns true if all leters in the word have been guessed

## words.js

- Exports IMDBs Top 50 Movies


## Built With

* [VSCode](http://www.dropwizard.io/1.0.2/docs/) - Code Editor
* [Node](https://nodejs.org/en/) - Application runtime environment that allows you to write server-side applications in JavaScript
* Good Ol' Javascript


## Authors

* **Christopher Bermudez** - *Homework From* - 2017-2018 UCF Coding Bootcamp

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

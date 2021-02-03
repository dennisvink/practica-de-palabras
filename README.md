# Practice Spanish words

This repository contains a single HTML web page. Its purpose is to allow you to
practice Spanish words (or English words). By default it contains three different
exercises:

- Days of the week
- Months
- Seasons

The words are embedded in the URL. For example: `https://drvink.com/palabres/#primavera,verano,otoño,invierno/spring,summer,fall,winter`

This URL dynamically creates a quiz (Spanish to English and English to Spanish) for the words in the URL.
Words after the pound sign (#) until the slash represent the Spanish words. The words after the slash are the English translation.

A demo is available at [https://drvink.com/palabres/](https://drvink.com/palabres/)

## Running it locally (Mac, Linux)

- Clone this repository
- cd into it
- Type: `python -m SimpleHTTPServer 8080`
- Go to https://localhost:8080
- Press one of the exercises in the bottom left
- or modify the words in the URL to practice other words


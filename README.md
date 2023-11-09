# Taylor Swift Lyrics Wordcloud implementation
In this project, we will use a database of Taylor Swift's song lyrics to create a wordcloud showing the most used words in her songs.
To achieve that, we will use a few libraries such as:
* os: for manipulating local directories
* re: for extraction of patterns in lyrics
* wordcloud: for creating the wordcloud object
* PIL: for creating an Image object and use it as mask for the wordcloud
* matplotlib: to plot the wordcloud

## Data
The data is obtained from ishijo's project which can be found [here](https://github.com/ishijo/Taylor-Swift-Lyrics).
The data is extracted using a Genius API and the lyrics of each song are in .txt format.

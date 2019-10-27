# Vulgar Dictionaries

Vulgar Dictionaries allows you to create searchable online conlang dictionaries (using Markdown formatting) and deploy your website to a free custom URL using Netlify.com.

## How to set up your dictionary

1. Sign up to GitHub
1. Clone this repository. (Help, how do I do this?)
1. Sign into Netlify.com with your GitHub account. You do not need to create a Netlify account. (Help, how do I do this?)
1. Edit this README.md file to change the Website Settings (title of website and language names) and the home page message
1. Edit dictionary files to create entires for words (see formatting instructions below)

# Website Settings

    Website title: My Conlang - English Dictionary
    Language A: Sfoda
    Language B: English
    
# Home page message

This your home page message. Edit me!

# Creating dictionary entries

There are two dicitonry files: ```conlang-dictionary.md``` contains the Conlang to English translations, and ```English-dictionary.md``` contains the English to Conalng translations.

A word entry begins with a single # symbol, and is followed by standard Markdown syntax to make sub-headings and lists:

    # word
    /pronunciation of word/
    ### noun
    1. definition one
    1. definition two
    
### Indented quotations

Quotations are indented by exactly 4 spaces. Sepearte translations with a dash symbol to trigger special qutation formatting:

    # mujer
    /muxer/
    ### feminine noun
    1. woman
        * la mujer canta - the woman is signing
        * las mujeres son maravillosas - women are amazing
    1. wife
        * e mi mujer - she is my wife

---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Home
nav_order: 0
layout: home
---

# Proto 
#### Updated 2021-07-25

<img width="200" src="/assets/IMG_5961.PNG"/>
<img width="200" src="/assets/IMG_5962.PNG"/>


## What is this?

Proto is a suite of high quality flash card decks for use in [Anki](https://apps.ankiweb.net), [spaced-repetition](https://en.wikipedia.org/wiki/Spaced_repetition) software for building your vocabulary in foreign languages.

The cards in Proto decks are divided into parts of speech (nouns, verbs, and adjectives) and are ordered by _decreasing frequency._ The first hundred words in each deck are the most common hundred words in that language, and so on. In other words, each new word you learn is slightly less useful than the last.

Each card gives you a word and asks you to produce its definition. Generally, each card has the word's definition in English and a playable sound file with a native speaker pronouncing the word.

## Why?

Some years ago, [I](https://sqweebloid.com/) noticed that most language decks made for Anki were not very good for a number of reasons:
* Their vocabulary lists were thematic, tied to textbooks, or incomplete
* Words had custom definitions written by the deck creator
* There were few useful features

As a polyglot who aims to get started in a language as quickly as possible, I wanted flashcards (a) with useful words and (b) that would let me mimic a native speaker. Since I'm a software engineer, I realized that I could write a program that generated suitable cards.

## How?

To create a new deck, I start by looking for word frequency lists. Often these come from institutions with departments that study the language and provide a [text corpus](https://en.wikipedia.org/wiki/Text_corpus) of the language in question. If I'm lucky, they offer a word frequency list tagged by part of speech.

I process these word lists and augment them with data like definitions, conjugations, declensions, and native speaker pronunciation, then I build them into Anki decks with custom Python software.

## License and distribution

I couldn't decide whether to distribute these beyond my immediate friends for years because I don't own the rights to the definitions, sounds, and other material. I attempted to attribute information on data sources where applicable, though I may have missed something. These materials are provided as-is and are strictly for educational purposes. These decks are not for commercial use, nor have I made money off them.

## Donations

That being said, I have invested hundreds of hours creating these decks over the past decade. Donations are unnecessary but appreciated.

* [Paypal](https://www.paypal.com/donate?business=WP2TJF2P42RHJ&no_recurring=0&item_name=Proto&currency_code=USD
)
* ETH (Coinbase or otherwise): `0x97C1F3b73df65492667D69355e226caE10B8162f`

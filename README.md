# Flashcard_App 

## Installation
Fork and clone this repo, then run `npm install` for the associated dependencies.

Run `npm start` to start the project 

## Basic Info
I made a flashcard web app for the Thinkful front-end capstone project. The app allows users to create and edit their own deck of flashcards and study with the flashcards. Users can add more cards to the deck and edit the cards.

The project was intended to be used as part of a study program using flashcards.

## Responsibilities
Design the layout of the app and implemented all required functionalities. 

## Routes
| Screen      | Path                                                  |
| ----------- | ----------------------------------------------------- |
| Home        | /                                                     |
| Deck        | /decks/:deckId                                        |
| Create Deck | /decks/new                                            |
| Edit Deck   | /decks/:deckId/edit                                   |
| Add Card    | /decks/:deckId/cards/new                              |
| Edit Card   | /decks/:deckId/cards/:cardId/edit                     |
| Study       | /decks/:deckId/study                                  |
| Study       | /decks/:deckId/study clicking flip shows next button  |
| Study       | /decks/:deckId/study not enough cards                 |

## Tech Stacks
* React
* React Router
* Bootstrap
* HTML
* CSS

## Home
![Home](/images/home.png)

## Deck
![Deck](/images/deck-deckId.png)

## Create Deck
![Create Deck](/images/create-deck.png)

## Edit Deck
![Edit Deck](/images/edit-deck.png)

## Add Card
![Add Card](/images/add-card.png)

## Edit Card
![Edit Card](/images/edit-card.png)

## Delete Deck
![Delete Deck](/images/delete-deck.png)

## Delete Card
![Delete Card](/images/delete-card.png)

## Study
### Front
![Study Front](/images/study-front.png)
### Back
![Study Back](/images/study-back.png)
### Not Enough Cards
![No Cards](/images/not-enough-cards.png)

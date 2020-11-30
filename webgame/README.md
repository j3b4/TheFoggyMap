# The Foggy Map Web Game
This directory contains specifications and code for a webpage that will support playing The Foggy Map on a computer or mobile device.

# Foggy Map Web Game Specifications
The page will have a short introduction and instructions for playing the game on a web page. The page should simulate the shuffling of the 
three decks: adjectives, nouns, and questions. The user will be able to change the word cards or the questions or re-shuffle all decks
at once.

## Instructions
The game concept in a sentence or two; the rules of play; and the interface manual for the webgame.

## Twine Features of the Foggy Map Web Game
The following features are by-products of the platform and story-format used to create the web game. We can either keep them or try
to engineer alternatives. 
* loading the page shuffles all three decks. 
  This is because the arrays questions, nouns, and adjectives are created using the (shuffled: $list) function. This means they are never
  presented to the player in the default order. This could be easily changed by adding another step.
* players change word or question cards by clicking on the text; when they have gone through the entire sequence the card disapears. 
  This is because the behaviour of the (cycling-link:) function in Harlowe. The options are to have it end on a fixed word that doesn't
  move - perhaps a signal to 'reshuffle' everything; or to let the words continue to cycle, going through the deck again in the same order.
 
 ## Formatting
 Presently the 

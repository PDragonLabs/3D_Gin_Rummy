# 3D_Gin_Rummy
3D Gin Rummy


[scr sht](Screenshot 2025-07-25 at 13-14-05 3D Gin Rummy.png)


3D Gin Rummy

Welcome to 3D Gin Rummy! This is a classic card game brought to life in a 3D environment, running entirely in your web browser. Play a single-player game against a computer AI, and enjoy the immersive experience built with HTML, CSS, and the power of Three.js.

(Screenshot 2025-07-25 at 13-14-05 3D Gin Rummy.png)
Features

    Immersive 3D Interface: Experience Gin Rummy on a virtual 3D table with animated cards and a clean, modern design.

    Challenging AI Opponent: Test your skills against a computer player with its own strategic logic.

    Intuitive Controls:

        Click-to-draw from the deck or discard pile.

        Click-to-discard from your hand.

        Drag-and-drop cards to organize your hand exactly how you like it.

    Full Game Logic: Implements standard Gin Rummy rules, including knocking, going Gin, undercuts, and scoring.

    No Setup Required: Runs directly in any modern web browser. No downloads or installations needed.

How to Play

The goal of Gin Rummy is to form your cards into melds and have less "deadwood" (unmelded cards) than your opponent.
The Basics

    Melds:

        Set: Three or four cards of the same rank (e.g., 7♠, 7♥, 7♦).

        Run: Three or more cards of the same suit in sequence (e.g., 4♣, 5♣, 6♣).

    Deadwood: Cards in your hand that are not part of a meld. Each card is worth its face value (Aces = 1, face cards = 10).

Your Turn

A turn consists of two actions: drawing a card and then discarding a card.

    Draw a Card:

        You must start your turn by taking one card. You have two choices:

            Draw from the Deck: Click on the face-down deck pile (or the "Draw from Deck" button).

            Draw from the Discard Pile: Click on the face-up card on the discard pile (or the "Draw from Discard" button).

    Discard a Card:

        After drawing, you will have 11 cards. You must discard one card to end your turn.

        To discard, simply click on any card in your hand. It will be moved to the discard pile.

Organizing Your Hand

    To make it easier to see your potential melds, you can rearrange the cards in your hand.

    Click and drag any card in your hand and drop it in a new position. The other cards will animate to make space.

Ending the Round (Knocking)

The round ends when a player "knocks."

    You can knock on your turn if your deadwood value is 10 points or less.

    The "Knock" button will appear after you draw a card if you are eligible to knock.

    After you knock, both you and the computer will lay down your melds.

    Scoring:

        If your deadwood is lower than the computer's, you score the difference.

        Going Gin: If you have zero deadwood, you get a 25-point bonus.

        Undercut: If the computer's deadwood is equal to or less than yours, the computer scores the difference plus a 25-point undercut bonus.

The game continues with new rounds until a player reaches a predetermined score (traditionally 100).
Setup

This project is self-contained in a single index.html file.

    Clone this repository or download the index.html file.

    Open the index.html file in a modern web browser like Chrome, Firefox, or Edge.

    That's it! The game will start automatically. Enjoy!

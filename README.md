# FlashFlow – Spaced Repetition Flashcard App

A single-page web application for learning with flashcards using a custom spaced repetition algorithm.

## Features
- Create and manage flashcard decks
- Custom interval-based spaced repetition (SR) algorithm
- Four-level rating system: Again / Hard / Good / Easy
- Statistics dashboard with streak tracking
- Dark/light mode toggle
- Import and export decks as JSON

## How to run
Open `index.html` in any modern web browser. No installation or dependencies required.

## SR Algorithm
Each card stores an interval (days until next review) and an ease factor.
Ratings adjust both values: Again resets the interval to 0, Hard keeps it,
Good multiplies by the ease factor, Easy multiplies by ease factor × 1.3.

## Built with
Vanilla HTML, CSS, and JavaScript. No frameworks or libraries.

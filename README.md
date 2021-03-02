# Flashcard-o-Matic

## About

Utilize React and Bootstrap to create a flash card web application where a user can create, edit, and delete a deck. Cards may be added, removed, or edited.
There is a study function for each deck with a 3 card minimum requirement to function, otherwise the user is given the option to add cards.

## Tools

- Installing packages with NPM
- React function components
- Routes using React Router
- Hooks including useState(), useEffect(), useParams(), and useHistory()
- Bootstrap v4.5
- Bootstrap Icons

## Structure

- index.js
  - App.js
    - Layout/index.js (Stateful)
      - CardForm "./Common/CardForm.js" (Stateful)
      - DeckForm "./Common/DeckForm.js" (Stateful)
      - Header "./Common/Header.js" (Stateless)
      - NotFound "./Common/NotFound.js" (Stateless)
      - ViewDeck "./Decks/ViewDeck.js" (Stateful)
        - ListCards "./Decks/ListCards.js" (Stateless)
      - Home "./Home/Home.js" (Stateful)
        - ListDecks "./Home/ListDecks.js"; (Stateless)
      - Study "./Study/Study.js" (Stateful)
        - StudyCard "./Study/StudyCard.js" (Stateless)

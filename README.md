# Quizdeck

Quizdeck is an array-driven practice quiz for a data structures assignment. It presents eight questions in order, lets a learner answer each one, gives immediate feedback, and calculates the final score.

The main data is the `questions` array. The current question is selected with an index. Each question has its own options array, and the answer index identifies the correct option. The interface also exposes one question in a readable array preview.

This is a static classroom prototype: no login, backend, payment, or database is required. Scores reset when the page is refreshed. Open `index.html` directly or serve the folder with any static server.

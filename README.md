# Flash-Card-Generator
Javascript App to Generate Flash Cards
Run and follow the instructions

```
At the command prompt type: node app.js
```

The first prompt will ask you what you would like to do. If you choose to
`add-flashcard`, you will be prompted to pick which type of flashcard you would
like to create. The options will be `basic-flashcard` or `cloze-flashcard`. More
information about these types below. Once you've created the flashcard it will
be appended to the `log.txt` file. You will then be asked if you would like to
`create-new-flashcard`, `show-all-cards`, `nothing`. Nothing will end the app,
`create-new-flashcard` will restart the flashcard creation process described
above.

If you choose to `show-all-cards`, each of the flashcards will be displayed to
you as a question (`front`) of the card. Your response will be compared to the
correct response (`back`) of the card. You will be shown each card until they
are exhausted. When they are exhausted the app will quit.



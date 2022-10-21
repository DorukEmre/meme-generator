React app to display a meme image from a fetched database with text input overlayed.

A meme component renders a styled form with 2 inputs and the button.
The component saved a database of memes as an array in state through fetch API on first render.

A button allows to scan the database and display one meme image.
The meme image is saved as state in a meme object.

Two inputs allow to superimpose text over the image as it is being typed by saving the value in the meme object.
Each change in the inputs triggers the save of a new state of the meme object.

## Difficulties while working on the project

The file references in the HTML file start with /.. Because of this the Chrome compiler was unable to locate the sources and the index.html file came up to be blank when first opened. It took a little while to understand that it was due to the href's in the html file. Kindly change those link names so that they begin with ./ instead.

In the Easy Task Description, it was a little ambiguous to me as to what it meant by "If they play multiple notes with less than 2.5 seconds between each note, you should wait them to finish". Hence, based on my understanding, I wrote the code so that once the user presses a button, they can still press another ones until 2.5 seconds and then it will start repeating the pattern as it was entered.


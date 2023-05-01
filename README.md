# Book Recomendations

The challenge of this project, part of the [Free Code Camp Machine Learning course](https://www.freecodecamp.org/learn/machine-learning-with-python/#how-neural-networks-work), was to build a Book Recommendation Engine using the K-Nearest Neighbors algorithm. The dataset used for training the model was the Book-Crossings dataset which contains 1.1 million ratings (scale of 1-10) of 270,000 books by 90,000 users.

All the data were treated using Pandas and the Nearest Neighbors algorithm was implemented using Scikit-learn.

The algorithm was designed to suggest five books that are similar to the input book based on the user’s rating for it and the book’s author.

For instance, for the book:

- Where the Heart Is (Oprah's Book Club (Paperback))

The algorithm will return the following recommendations:

- I'll Be Seeing You
- The Weight of Water
- The Surgeon
- I Know This Much Is True
- The Lovely Bones: A Novel

And the distance of each recommendation to the input book calculated by the KNN algorithm.

<p align="center">
  <img src="./docs/NN.jpg" height=500px>
</p>

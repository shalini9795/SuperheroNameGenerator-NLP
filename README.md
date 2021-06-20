# SuperheroNameGenerator-NLP
Auto completes superhero names based on letters typed

In this project, we are going to create a neural network and train it on a small dataset of superhero names to learn to generate similar names. The dataset has over 9000 names of superheroes, supervillains and other fictional characters from a number of different comic books, TV shows and movies.Text generation is a common natural language processing task. 

We will create a character level language model that will predict the next character for a given input sequence.

In order to get a new predicted superhero name, we will need to give our model a seed input - this can be a single character or a sequence of characters, and the model will then generate the next character that it predicts should after the input sequence. This character is then added to the seed input to create a new input, which is then used again to generate the next character, and so on.

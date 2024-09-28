# WordVectorInMotion
A real-time video demonstration of how word embeddings are trained, visually displaying how meaning emerges and changes.

WordVectorInMotion is a unique visualization tool that demonstrates how word embeddings are trained and evolve over time. By visualizing the semantic relationships between words, the tool provides a captivating view of how similar words move closer together as they gain meaning during the training process, while dissimilar words drift apart. The tool generates a video showcasing this transformation.

![Video Preview](assets/WordVectorInMotion.gif)

## Features
* Dynamic Visualization: Watch word embeddings evolve as the training progresses, with similar words converging.
* Semantic Relationships: Visualizes how words of similar meanings cluster closer together over time.
* Educational: Great for understanding how word embeddings, such as Word2Vec, GloVe, or Transformer-based embeddings, capture semantic meaning.
* Video Output: Generates a video of the entire training process, allowing users to observe word vectors in motion.

## Installation
To run WordVectorInMotion locally, follow these steps:

Clone the Repository:

``` 
git clone https://github.com/Vik3927/WordVectorInMotion.git
```

Navigate to the Project Directory:

```
cd WordVectorInMotion
```

Install the Required Dependencies:

```
pip install -r requirements.txt
```

## Usage
You can run the tool through a Jupyter notebook, which will generate a dynamic video showing the progression of word embeddings during training.

Launch the Jupyter Notebook:

```
jupyter notebook
```

Run the Notebook: Open the `Training and Visualising Word Embeddings.ipynb` notebook and run the cells. You can specify different parameters such as:

Word list: You can provide your vocabulary in a txt file as lines
Training epochs: Adjust the number of epochs to visualize more or less movement.
Generate the Video: After running the notebook, the output video will be generated showing the word embeddings in motion.

## Contributing
Contributions are welcome! If you'd like to contribute to WordVectorInMotion, please follow these steps:

* Fork the repository.
* Create a new branch (git checkout -b feature-branch).
* Commit your changes (git commit -m 'Add some feature').
* Push to the branch (git push origin feature-branch).
* Open a pull request.

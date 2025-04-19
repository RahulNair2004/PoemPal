
# Poem Analysis Tool

This tool leverages state-of-the-art Natural Language Processing (NLP) models to analyze poems in terms of their **poetic form**, **poetic theme**, and **sentiment**. By utilizing a combination of models such as **BERT**, **BiLSTM**, **Graph Neural Networks (GNN)**, and **RoBERTa**, the tool provides a comprehensive analysis of various aspects of a poem.

## Features

- **Poetic Form Analysis**: Detects the structure of the poem and identifies the underlying poetic form of the poem.
- **Poetic Theme Identification**: Identifies the underlying themes in the poem such as love, nature, loss, etc., using advanced theme detection models.
- **Sentiment Analysis**: Analyzes the sentiment conveyed in the poem (positive, negative, neutral) using sentiment models built on **BiLSTM** and **RoBERTa**.

## Requirements

- Python 3.x
- PyTorch
- HuggingFace Transformers
- TensorFlow (for BiLSTM)
- NetworkX (for GNN)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/RahulNair2004/poem-analysis-tool.git
   cd poem-analysis-tool
   ```
## Model Architecture

- **BERT** and **RoBERTa** are used for understanding the semantic context of the poem.
- **BiLSTM** models capture long-term dependencies in the text to classify sentiment and themes.
- **GNN** is applied to capture relational structures between words/phrases within the poem, aiding in identifying hidden themes and connections.

## Example Output

```bash
Poem: "The sun sets over the mountains, painting the sky with hues of gold."
Poetic Form: [Rhyme scheme: ABAB, Stanza format: 4-line stanza, Meter: Iambic Pentameter]
Poetic Theme: Nature, Beauty
Sentiment: Positive
```

## Training Your Own Models

If you would like to train your own models or fine-tune existing ones, follow these steps:

1. Prepare your training data (poem dataset with corresponding labels).
2. Train BERT, BiLSTM, and GNN models using the provided scripts.
3. Fine-tune the models on your dataset to improve performance.


## Contribution

Feel free to contribute to this project by submitting issues or pull requests. All contributions are welcome.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **HuggingFace Transformers** for providing the pre-trained models.
- **PyTorch** and **TensorFlow** for deep learning frameworks.
- The open-source community for continuous contributions and support.

---

Let me know if you'd like to make any adjustments or add more details!

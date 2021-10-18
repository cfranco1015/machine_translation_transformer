# Machine Translation

## Description

A sequence-to-sequence Transformer model was built for Engilsh-to-Spanish machine translation. The Transformer architecture was built from three subcomponents: Encoder, Decoder and Positional Embedding. The dataset is available at https://www.manythings.org/anki/, where ~130k samples were taken from the Tatoeba Project. Word frequency distributions were generated for both the source and target languages. Text data was vectorized and formatted for model training. Test English  sentences were set aside to examine how well translation is done on unseen data samples. Users can also input their own English sentences and be outputted Spanish sentence inferences. Intution behind Transformers and their role in machine translation can be found [here](http://peterbloem.nl/blog/transformers) and [here](https://www.tensorflow.org/text/tutorials/transformer) respectively.

## Dependencies
* Tensorflow 2 
* NLTK
* NumPy
* Matplotlib
* Scikit-learn

### Executing program

Notebook can be ran using Google Colab or Jupyter Lab. It can also be downloaded as a .py file and ran using: 
```
python3 machine_translation_transformer.py
```

## Help
* Transformer models should be trained on data for at least thirty epochs
* Adding custom layers to the overall model will need an overridden get_config() function for proper model saving/loading.

## License

The Anki data is licensed under the CC-BY License. 

## Acknowledgments
This repository was greatly influenced by [fchollet](https://github.com/keras-team/keras-io/blob/master/examples/nlp/neural_machine_translation_with_transformer.py).

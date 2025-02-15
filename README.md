# Implementation of EMPATH on Brazilian Sign language (LIBRAS) recognition to sign language dataset creatio

This project is a proof of concept on the creation of a Brazilian Sign Language (LIBRAS) dataset based on the implementation of Ensemble Learning with Attention-based Transformer (EMPATH), a sign language recognition specialized algorithim with 97% accuracy on the recognition of brazilian sign language.

The project is divided in two parts, one called [transformer_training.ipynb](transformer_training.ipynb) used to process the data using media pipe to create parquet files to normalize the model inputs, and train the EMPATH model for LIBRAS recognition, and the other called [finalizacao.ipynb](finalizacao.ipynb) used to implement the EMPATH model on congress sessions to proof the possibility of creating a dataset using this methodlogy.

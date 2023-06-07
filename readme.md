# Music Generation using Transformers
To generate music using musical notes in a non-trivial way, unlike generating it from the actual sound waves. We propose to create a model to generate music based on a few initial notes from the music MIDI file provided. The basic principle is to build a sequence model for music. That is, take an input sequence and predict a target sequence. We put forward a solution based on transformers to modify music notes to tokens in an auto-regressive manner as a part of a single input stream. The traditional approach of music generation using Recurrent Neural Networks has to learn to proactively store elements to be referenced in a fixed-size state or memory, making training potentially more difficult. To optimize this problem we are using concepts of transformer that can help capture the multiple levels at which self-referential phenomena exist in music. The project is implemented with a MLOps fashion.

## Results
[EE641_Final_Report.pdf](https://github.com/Divya-Nandlal-Sahetya/Music-Generation-Using-Transformers/files/11681257/EE641_Final_Report.pdf)

## Papers
https://arxiv.org/abs/1809.04281

## Video
https://github.com/Divya-Nandlal-Sahetya/Music-Generation-Using-Transformers/assets/97777124/cde110c7-ab01-43f1-941e-d01bd5ccf8c1


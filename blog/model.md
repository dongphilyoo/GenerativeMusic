### Onset and Frames - Magenta</br></br>

__What is it?__</br>

_automatic polyphonic piano music transcription_</br>
[Paper](https://arxiv.org/pdf/1710.11153.pdf)</br>
convert raw recordings of solo piano performances into MIDI</br>
[Musical information retrieval](https://en.wikipedia.org/wiki/Music_information_retrieval)

<img src="https://magenta.tensorflow.org/assets/onsets_frames/onsets-frames-logo.png" width="40%" /></br></br>

__Which neural network?__</br>

__CNNs + LSTMs__</br>
[_learn more_](https://www.quora.com/Where-does-each-type-of-neural-network-RNN-CNN-LSTM-etc-excel)

![](https://i.imgur.com/jR2eYgc.jpg)

__Network Architecture__</br></br>

<img src="https://magenta.tensorflow.org/assets/onsets_frames/networkstack9.png" width="50%" /></br></br>

__Inference__</br></br>
restricting model output based on the onset detector</br>
[Onset Detection](https://musicinformationretrieval.com/onset_detection.html)

<img src="https://magenta.tensorflow.org/assets/onsets_frames/frames.png" width="55%" /></br>

__Resources__</br></br>
[repo](https://github.com/tensorflow/magenta/tree/master/magenta/models/onsets_frames_transcription)</br>
[Colab notebook](https://colab.research.google.com/notebooks/magenta/onsets_frames_transcription/onsets_frames_transcription.ipynb)</br>
[Magenta discuss](https://groups.google.com/a/tensorflow.org/forum/#!forum/magenta-discuss)</br>
[piano scribe](https://piano-scribe.glitch.me/)

---
title: "Neural Networks for Segmentation of Vocalizations"
collection: talks
type: "Talk"
permalink: /talks/2017-11-27-neural-networks-for-segmentation-of-vocalizations
venue: "PyData NYC 2017"
date: 2017-11-27
location: "New York, New York"
---
Neural networks for speech-to-text avoid dividing speech into segments, such as syllables, but segmenting has important applications. We compare different neural networks for segmentation of vocalizations using the song of songbirds, which we study as neuroscientists. Initial results suggest a bidirectional LSTM-CNN architecture outperforms others in both segmentation and classification.

Talk on YouTube: <https://youtu.be/1XEDFpUGmqs>

## Abstract
Neural networks for speech-to-text continue to set new records for accuracy. These networks succeed in large part because they explicitly avoid dealing with the issue of dividing speech into some sort of segment, like a syllable or a phoneme [^1]. However there are many use cases, such as diagnosis of speech disorders, where automated segmentation could have great impact.

One difficulty with speech segmentation is that it requires hand-segmented and labeled training data. In addition, in speech the beginning and end of syllables is often not clear. In contrast, the songs of many species of songbird consist of elements that are clearly separated by brief silences. Because of these brief silences, birdsong can typically be segmented automatically. Furthermore in many species an individual will have a small number of elements in their song, relative to the many different syllables and words that make up a language. Hence birdsong provides a convenient way to test different architectures that segment vocalizations and then label those segments.

In this talk, we discuss our results comparing neural net architectures for segmentation of vocalizations, using an open repository of birdsong to benchmark them. These networks for segmentation also provide a useful tool for neuroscientists that study songbirds as a model system to understand how the brain learns speech and similar motor skills, as we will explain. Preliminary results suggest that a bidirectional LSTM-CNN network [^2][^3][^4] outperforms other architectures, such as fully convolutional networks [^5][^6][^7], in terms of classification and segmentation. We will discuss the implications of the results for researchers in applied neural networks.

[^1]: Graves, Alex. Supervised sequence labelling with recurrent neural networks. Vol. 385. Heidelberg: Springer, 2012.

[^2]: S. Böck and M. Schedl, "Polyphonic piano note transcription with recurrent neural networks," 2012 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Kyoto, 2012, pp. 121-124.

[^3]: Parascandolo, Huttunen, and Virtanen, “Recurrent Neural Networks for Polyphonic Sound Event Detection in Real Life Recordings.”

[^4]: <https://github.com/yardencsGitHub/tf_syllable_segmentation_annotation>

[^5]: Long, Jonathan, Evan Shelhamer, and Trevor Darrell. "Fully convolutional networks for semantic segmentation." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2015.

[^6]: Yu, Fisher, and Vladlen Koltun. "Multi-scale context aggregation by dilated convolutions." arXiv preprint arXiv:1511.07122 (2015).

[^7]: Koumura, Takuya, and Kazuo Okanoya. "Automatic Recognition of Element Classes and Boundaries in the Birdsong with Variable Sequences." PloS one 11.7 (2016): e0159188.

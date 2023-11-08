# META4: Semantically-Aligned Generation of metaphoric gestures using self-supervised text and speech representations
## Authors: Mireille Fares, Catherine Pelachaud, Nicolas Obin

This is the official repository for the paper "*META4: Semantically-Aligned Generation of metaphoric gestures using self-supervised text and speech representations*". It contains the training and testing code of META4.

Bibtex:
```ruby
@article{fares2023META4,
  title={META4: Semantically-Aligned Generation of metaphoric gestures using self-supervised text and speech representations},
  author={Fares, Mireille and Pelachaud, Catherine and Obin, Nicolas},
  journal={arXiv preprint arXiv:XXX.XXX},
  year={2023}
}
```

**Abstract**: Image Schemas are repetitive cognitive patterns that influence the way we conceptualize and reason about various concepts present in speech. These patterns are deeply embedded within our cognitive processes and are reflected in our bodily expressions including gestures. Particularly, metaphoric gestures possess essential characteristics and semantic meanings that align with Image Schemas, to visually represent abstract concepts. The shape and form of gestures can convey abstract concepts, such as extending one's forearm and hand or tracing a line with hand movements to visually represent the image schema of "PATH". Previous behavior generation models have primarily focused on utilizing speech (acoustic features and text) to drive the generation model of virtual agents. They have not considered key semantic information as those carried by Image Schemas to effectively generate metaphoric gestures. To address this limitation, we introduce META4, a deep-learning approach that generates metaphoric gestures from both speech and Image Schemas. Our approach has two primary goals: (1) computing Image Schemas from input text to capture the underlying semantic and metaphorical meaning, and (2) generating metaphoric gestures driven by speech and the computed image schemas. We make two key contributions: (1) BERTIS, a model that computes Image Schema tags from text input, and (2)  META4, which makes use of BERTIS to model and synthesize the corresponding metaphoric gestures from speech and the generated Image Schemas. To the best of our knowledge, our approach is the first method for generating speech-driven metaphoric gestures while leveraging the potential of Image Schemas. We present evaluation studies to demonstrate the effectiveness of our approach and highlight the importance of both speech and image schemas in modeling metaphoric gestures.

- [Code of BERTIS](https://github.com/mireillefares/BERTIS/blob/main/README.md)
- [BERTIS trained Model](https://huggingface.co/mireillfares/BERTIS)

The following videos show META4's predictions:  [Simulation 1](https://youtu.be/BMwS8p2UCGg), [Simulation 2](https://youtu.be/ecomhnit6XY), [Simulation 3](https://youtu.be/99ipLHhmJOM)

## Other cool stuff
[BERTIS](https://github.com/mireillefares/BERTIS/blob/main/README.md)


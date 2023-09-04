# Novel-Object-Captioning-Experiment
Reproduction of *Deep Compositional Captioning: Describing Novel Object Categories without Paired Training Data* and *Captioning Images with Diverse Objects*, with some minor changes in the equivocal points. The subject is to train a generative model with a image encoder and a text decoder, which can caption images with novel objects, namely those excluded in the paired training data. (However, the image encoder has seen the object and the text decoder know the its name, so some similarity mechanism is applied to achieve the subject.)

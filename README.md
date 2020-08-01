# Prostate-cANcer-graDe-Assessment-PANDA-Challenge
My teams entry in Kaggle's Prostate cANcer graDe Assessment (PANDA) Challenge competition

### The pipeline for the competition:
1. `image export.ipynb` to preprocess the images
2. `Densenet169_progressive_resize_343.ipynb` and `Densenet_169_round_2.ipynb` are examples of model training notebooks (there are many similar notebooks that were also used to train the dozens of models we experimented with)
3. `Pandas-model-evaluaion-and-blend-selector.ipynb` was used to evaluate the performance of combinations of models (we used a blended approach for submissions)
4. `final-submission.ipynb` the notebook for submitting our work to the competition.
 
### Other notebooks:
* `threshold-expirements.ipynb` was used to test if manually tweaking the thresholds for each classification would improve performance. the difference was ultimately not significant enough to pursue further
* `striplicate` This preprocessing method fills the empty whitespace in an image by taking image data from rotated versions of the image, unfortunately this wasn't used in our final pipeline. Showed great promise but we failed to implement it in time (see post mortem for full details)
* `post-mortem`, this file is the writeup for our teams performance in the competition. what lessons we took away, what worked, what we would do better next time, and what opportunities did we miss.

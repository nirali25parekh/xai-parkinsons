# Parkinson’s Disease Detection- An Interpretable Approach to Temporal Audio Classification

### Paper Published [here](https://ieeexplore.ieee.org/document/9971881)
Authors: Raj Shah, Bhavi Dave, Nirali Parekh and Kriti Srivastava

### Abstract
Model Interpretability is critical for analyzing the
potential risks inherent to the utilization of black-box neural
networks in the medical domain. The current methodologies
for Parkinson’s disease (PD) detection require expertise from
medical professionals alongside an expensive and time-consuming
procedure. AI-driven Deep Learning (DL) models have generated
state-of-the-art performance and have the potential to improve
the process of PD detection by leveraging the early stage
symptom of vocal deterioration to enable early identification
of the disease. However, the potential of DL for PD selection
has remained untapped thus far because of the lack of model
interpretability and the possibility of even an accurate model
failing to capture the correct causal relationship between the
input signal and the prediction. This work implements a neural
network that contains vowel phonations. The model achieved a
classification accuracy of 90.32% with a precision, recall and
F1 Score of 0.91, 0.90 and 0.905. A novel model interpretation
algorithm is proposed that divides the audio file into logical
chunks and provides a category label identifying the productivity
of each chunk towards correct inference. This is based on its
interactions with every other audio region in the file, and the
effective change of model performance and confidence with its
inclusion. An audio instance within a clip is significant for desired
output only in conjunction with other audio regions that together
generate a meaningful pattern indicating the existence of PD.
The algorithm also ranks all audio chunks in the order of their
importance to the correct prediction by analyzing the degree
in which their impact varies when combined with other audio
regions. This paper demonstrates that DL can be leveraged to
create a reliable, accurate, and efficient method for PD Detection
and the model can be extended to provide interpretability to the
inferences in a way that is scalable, and free from bias

### Cite as: 
```
@INPROCEEDINGS{9971881,
  author={Shah, Raj and Dave, Bhavi and Parekh, Nirali and Srivastava, Kriti},
  booktitle={2022 IEEE 3rd Global Conference for Advancement in Technology (GCAT)}, 
  title={Parkinson's Disease Detection - An Interpretable Approach to Temporal Audio Classification}, 
  year={2022},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/GCAT55367.2022.9971881}}
```

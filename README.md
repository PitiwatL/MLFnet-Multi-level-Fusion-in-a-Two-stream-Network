# Test
The explanation is during in preparation....
Optical Flow Videos <br><br>
<div align="center">  
  <img src = "./assets/rgb_makeup.gif" width = 250>
  <img src = "./assets/makeup_opt.gif" width = 250>
  <img src = "./assets/makeup_inverted_opt.gif" width = 250>
</p>

Separate Stream
| Model | Result (%) | 
|:-------------------------------:|:--------:|
| Spatial Stream  (VGG16 + LSTM)         | 88.51 | 
| Temporal Stream (DenseNet121 + LSTM)   | 87.27  |  

Combined Stream S: (VGG16 + LSTM) + T: (DenseNet121 + LSTM)
| Late Fusion Methods | Result (%) | 
|:-----------:|:--------:|
| Averaged Sum | - | 
| Ridge Regression |  |
| Multinomial Naive Bayes |  |
| Majority Voting for these 3 Late fusion models |  |

Intermediate Fusion (Fusion inside Model) ()
| Intermediate Fusion Methods | Result (%)  | 
|:---------------------------:|-------------|
| Sum Fusion                  |  -  |       | 
| Max Fusion                  |     |       |
| Concatenation Fusion        |     |       |
| Convolution Fusion          |     |       |


Split Abnormal ECG Data into Training and Testing Sets:
Training Data Size: 
       17514         188

Testing Data Size: 
        4378         188

Split Normal ECG Data into Training and Testing Sets:
Training Data Size: 
        3998         141

Testing Data Size: 
        1000         141

Noisy Normal Training Data:
    0.2542
    0.3725
   -3.0330
   -1.2173
    5.0140
    1.0138
   -0.3757
   -0.5448
    0.7547
   -0.0750

Noisy Abnormal Training Data:
    0.3292
    1.2766
    0.5317
    1.1549
    1.2107
    0.8043
    0.8276
    1.0236
    1.4363
    0.6488

Filtered Noisy Normal Training Data:
    0.8870
    1.0017
   -2.4073
   -0.5952
    5.6326
    1.6289
    0.2358
    0.0632
    1.3593
    0.5261

Filtered Noisy Abnormal Training Data:
   -0.2726
    0.6725
   -0.0746
    0.5464
    0.5999
    0.1913
    0.2124
    0.4062
    0.8166
    0.0269

Statistical Features of ECG Signals:
           Feature            Normal_ECG    Abnormal_ECG
    ______________________    __________    ____________

    {'Mean'              }    0.0032233       0.00097   
    {'Standard Deviation'}       1.2553       0.55501   
    {'Max'               }       5.6326        2.3286   
    {'Min'               }        -5.52       -2.5433   
    {'RMS'               }       1.2551         0.555   
    {'Peak-to-Peak'      }       11.153         4.872   

Combined Feature Data for Classification:
                             combined_features                              labels
    ____________________________________________________________________    ______

     0.88702           0     0.88702     0.88702     0.88702           0      0   
      1.0017           0      1.0017      1.0017      1.0017           0      0   
     -2.4073           0     -2.4073     -2.4073      2.4073           0      0   
    -0.59519           0    -0.59519    -0.59519     0.59519           0      0   
      5.6326           0      5.6326      5.6326      5.6326           0      0   
      1.6289           0      1.6289      1.6289      1.6289           0      0   
     0.23578           0     0.23578     0.23578     0.23578           0      0   
    0.063184           0    0.063184    0.063184    0.063184           0      0   

No NaN values in combined features.
SVM model trained successfully.
  ClassificationSVM
             ResponseName: 'Y'
    CategoricalPredictors: []
               ClassNames: [0 1]
           ScoreTransform: 'none'
          NumObservations: 21512
                    Alpha: [7875x1 double]
                     Bias: 1.5488
         KernelParameters: [1x1 struct]
           BoxConstraints: [21512x1 double]
          ConvergenceInfo: [1x1 struct]
          IsSupportVector: [21512x1 logical]
                   Solver: 'SMO'


  Properties, Methods

Confusion Matrix:
         171         829
           7        4371

Accuracy: 0.84455
Precision: 0.84058
Recall: 0.9984

![image](https://github.com/user-attachments/assets/cf3c86c9-b541-457e-b8c7-77416d3c4cf6)


![image](https://github.com/user-attachments/assets/6820274d-dafd-4fad-a085-857fadcf1e86)

![image](https://github.com/user-attachments/assets/e58e068b-e8d9-40bc-a643-3414f548c5a3)





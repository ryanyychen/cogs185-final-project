Select 3 of:  
- structural SVM
- maximum margin Markov networks
- conditional random fields
- auto-context/fixed point


## SSVM:
### L = 1
#### 8/2
Training:  
91.17 s | 0.6945  
Testing:  
2.74 s | 0.6860  
Prediction:  
23.56 s | 0.0000  
#### 5/5
Training:  
55.74 s | 0.7048  
Testing:  
6.80 s | 0.6840  
Prediction:  
23.62 s | 0.0000  
#### 2/8
Training:  
22.38 s | 0.7260  
Testing:  
10.90 s | 0.6703  
Prediction:  
23.61 s | 0.0000  

### L = 2
#### 8/2
Training:  
1034.76 s | 0.4810  
Testing:  
19.07 s | 0.4400  
Prediction:  
141.46 s | 0.0000  
#### 5/5
Training:  
633.69 s | 0.5032  
Testing:  
47.78 s | 0.4468  
Prediction:  
141.34 s | 0.0000  
#### 2/8
Training:  
224.21 s | 0.5840  
Testing:  
76.44 s | 0.4473  
Prediction:  
141.92 s | 0.0000 

### L = 3
#### 8/2
Training:  
2242.64 s | 0.3335  
Testing:  
45.24 s | 0.3050  
Prediction:  
279.48 s | 0.0000  
#### 5/5
Training:  
1599.36 s | 0.3484  
Testing:  
114.93 s | 0.2964  
Prediction:  
287.02 s | 0.0000
#### 2/8
Training:  
672.66 s | 0.3980  
Testing:  
178.97 s | 0.2578  
Prediction:  
283.41 s | 0.0000

## CRF:
### L = 1
#### 8/2
Training:  
22.77 s | 0.8749  
Testing:  
0.18 s | 0.8500  
Prediction:  
0.18 s | 0.0.4990  
#### 5/5
Training:  
15.56 s | 0.8863  
Testing:  
0.49 s | 0.0.8293  
Prediction:  
0.49 s | 0.4504  
#### 2/8
Training:  
6.24 s | 0.8972  
Testing:  
0.80 s | 0.8042  
Prediction:  
0.80 s | 0.4015  

### L = 2
#### 8/2
Training:  
57.19 s | 0.9278  
Testing:  
0.57 s | 0.8269  
Prediction:  
0.57 s | 0.4590  
#### 5/5
Training:  
34.64 s | 0.9468  
Testing:  
1.41 s | 0.8050  
Prediction:  
1.41 s | 0.4048  
#### 2/8
Training:  
14.51 s | 0.9797  
Testing:  
2.13 s | 0.7685  
Prediction:  
2.13 s | 0.3247 

### L = 3
#### 8/2
Training:  
57.36 s | 0.9245  
Testing:  
0.58 s | 0.8285  
Prediction:  
0.58 s | 0.4550  
#### 5/5
Training:  
35.21 s | 0.9468  
Testing:  
1.57 s | 0.8141
Prediction:  
1.57 s | 0.4164
#### 2/8
Training:  
15.50 s | 0.9817  
Testing:  
2.28 s | 0.7591  
Prediction:  
2.28 s | 0.3205
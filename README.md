# EVA_S8

### Experiment : 
    To Test ResNet18 Architecture on Cifar10 Dataset
    
### Target:
    Achieve atleast 85% accuracy on Test Dataset of Cifar10 using ResNet18 model and modularise the code 
    
### Result:
Trained Resnet18 model on Cifar10 dataset with learning rate of 0.001 and 

Learning Rate	Update LR after few epochs	Epochs	Regularisation	Train Accuracy	Test Accuracy	Remarks
0.001	No	20	No	100%	78%	Overfitting
0.001	LR/3 after  every10 epochs	30	No	100%	84%	Overfitting
0.001	LR/3 after  every10 epochs	30	L2 weight decay = 0.005	100%	82%	Still Overfitting
0.001	LR/3 after  every10 epochs	30	L2 weight decay = 0.01	99%	84%	Still Overfitting
0.0005	LR/3 after  every10 epochs	25	L2 weight decay = 0.2	93%	87%	Better Model


| Attempt | #1 | #2 |
| :---: | :---: | :---: |
| Seconds | 301 | 283 |

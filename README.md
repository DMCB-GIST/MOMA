# MOMA: A Multi-task Attention Learning Algorithm for Multi-omics Data Interpretation and Classification

MOMA is a **multi-task attention learning model** that provides a general classification framework for **multi-data**. <br/>
MOMA can capture **important biological processes for high diagnostic performance** and **interpretability**.<br/>
The model vectorizes features and modules using a geometric approach, and focuses on important modules in multi-omics data via an attention mechanism.

###  We found that there was a download error related to the supplementary material, so we uploaded the file. 

* * *
⭐⭐⭐<br/>
**The appropriate hyperparameters are different according to various multi-modal data and tasks.<br/>**
 **The following is an empirical priority order, and it is recommended to put it on the tuning list at a minimum.<br/>**
 **Number of module = 16, 32, 64, 128, ... <br/>**
 **LearningRate = 5e-7, 5e-6, 5e-5, 5e-4, ... (with ADAM on PyTorch) <br/>**
 
* * *
## MOMA workflow
<img src="https://user-images.githubusercontent.com/37695581/108037054-62285c80-707c-11eb-9048-380fac6e58d8.jpg" width="90%" height="90%"> 
<br/>
<img src="https://user-images.githubusercontent.com/37695581/108036374-7d469c80-707b-11eb-9392-1498bd00be32.png" width="90%" height="90%">

## Example
Check dependencies in requirements.txt, and necessarily run
```
pip install -r requirements.txt
```
Example codes that employ MOMA to build classifiers of simulation data are included in the /[Example/](https://https://github.com/DMCB-GIST/MOMA/tree/main/Example)   folder and /[MOMA/MOMA_toy_example.ipynb](https://https://https://github.com/DMCB-GIST/MOMA/blob/main/MOMA/MOMA_toy_example.ipynb).<br/>

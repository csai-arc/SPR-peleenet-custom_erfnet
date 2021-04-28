# SPR-peleenet-custom_erfnet

### File descriptions:

**train_ERFNet.prototxt** - contains ST-ERFNet decoder training architecture.
**deploy_ERFNet.prototxt** - contains ST-ERFNet decoder inference architecture for classification.

**SPR_PeleeNet_architecture_overview.jpg** - PeleeNet architecture overview table.
![Alt text](/SPR_PeleeNet_architecture_overview.jpg?raw=true)

**train_Peleenet_cml.prototxt** - contains PeleeNet encoder training architecture based on combined margin loss.
**deploy_Peleenet_cml.prototxt** - contains PeleeNet encoder inference architecture for feature embeddings.

**Ablation_experiments_summary.jpg** - Comparitive list of the the ablation experiments conducted in terms of number of parameters, accuracy, precision and recall.
![Alt text](/Ablation_experiments_summary.jpg?raw=true)
Note: Encoder: PeleeNet+CML, Decoder: ST-ERFNet is our proposed method.


### Folder descriptions:

**Evaluation_results** folder contains the confusion matrix for these models.

**Ablation_studies** folder contains the accuracy, precision and recall metric values along with the confusion matrix for experiments conducted on other network architectures for comparison.

For Pre-trained network models please contact saipradeep.chakka@iiitb.ac.in


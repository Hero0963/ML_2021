# ML2021 is a course taught by HUNG-YI LEE (李宏毅).

#  source: https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html

## note: task06 encounters "The notebook took too long to render." issue
temporary solution (nbviewer): https://nbviewer.org/github/Hero0963/ML_2021/blob/main/ML_2021_hw06.ipynb

## task01 COVID-19 Cases Prediction
- pick features
- tune hyper_paras
- implememt L2 regularization  

## task02 Phoneme Classification
- batch norm
- dropout

## task03 Image Classification
- image_augmentation
- cnn model
- resnet18 model
- visualize the training progress
- save best performance model
- semi-supervised learning
     
## task04 Speaker classification
- conformer (cnn+transformer)


## task05 Machine Translation
- beam search 
- cross entropy
- transformer


## task06 Anime Face Generation
- wGAN

## task07 BERT - Question Answering
- model = BertForQuestionAnswering.from_pretrained("bert-base-chinese").to(device)

- tokenizer = BertTokenizerFast.from_pretrained("bert-base-chinese")

- change value of doc_stride
- randomize window position
- apply linear learning rate decay
- change "fp16_training" to True
- gradient accumulation

## task08 Anomaly Detection
- conv_autoencoder
- ROC_AUC score


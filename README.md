# Leaf-Count-Prediction

A Deep Learning Case Study that aims at automating the tedious task of observing Plant Phenotypes(leaves in this case). Given a plant image, it can predict the leaf count which can help monitor the health and growth of the plants. The approach involved using various Deep Learning technqiues using Segmentation models, Convolutional models for Regression and Transfer Learning models for predicting the leaf count. The best model was demonstrated using a webapp developed using Streamlit and hosted on Heroku.

Checkout the blog for detailed approach: [Let me count the leaves for you — A Deep Learning Case Study](https://towardsdatascience.com/let-me-count-the-leaves-for-you-a-deep-learning-case-study-687c24e5ac8a)

Streamlit Webapp link: [Leaf Count prediction app](https://leaf-counting-app.herokuapp.com)

Note: Since the app is hosted on a free account, in some instances it might take some time for the app to load and the prediction time may vary as well for some cases.

## Dataset:
1. M. Minervini, A. Fischbach, H.Scharr, and S.A. Tsaftaris. Finely-grained annotated datasets for image-based plant phenotyping. Pattern Recognition Letters, pages 1–10, 2015, doi:10.1016/j.patrec.2015.10.013 [[PDF]](http://ac.els-cdn.com/S0167865515003645/1-s2.0-S0167865515003645-main.pdf?_tid=b857c56c-9519-11e5-921f-00000aacb362&acdnat=1448637520_94632de233f4b8429a1727c827d4b8ac) [[BibTex]](https://www.plant-phenotyping.org/lw_resource/datapool/_items/item_338/minerviniprl2015.bib) 
2. [plant-phenotyping.org](https://www.plant-phenotyping.org/datasets) [[BibTex]](https://www.plant-phenotyping.org/lw_resource/datapool/_items/item_339/plantphenotypingdatasets.bib)

## Reference for Model Architectures:
Shubhra Aich and Ian Stavness. [Leaf Counting with Deep Convolutional and Deconvolutional Networks](https://arxiv.org/abs/1708.07570)

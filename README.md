# Recommender System model
I choose this topic in NTU_MBDS_DeepLearning course
The code is inside the "BS6204 project.ipynb", Other files save the trained model with training history.
### Dataset:
* **Moive_lens-100k**
### Data engineering
* The data was cleaned and the user history behaviours are extracted.
* The final data contains human sequential behaviours,user features, movie features and other context characteristics.
### Model:
* Base_embedding_model```AUC: 0.744```
* deep_crossing```AUC: 0.76```
* nuerual_cf```AUC: 0.767```
* wide_deep```AUC: 0.775```
* AFM```AUC: 0.731```
* DIN```AUC: 0.7789```
* DIEN without negative samples.```AUC0.7798```
### performance table and graph:
* Table:

![Performance_table](https://github.com/Niyx52094/figures/blob/main/result_table.png)
* Bar_chart:

![Performance_graph](https://github.com/Niyx52094/figures/blob/main/result_graph.png)
* AUC_curve:

![AUC_curve](https://github.com/Niyx52094/figures/blob/main/AUC_curve.png)


 

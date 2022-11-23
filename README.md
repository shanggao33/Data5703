# Data5703

![allstr](./images/allstr.png)

Hi, this is our ensemble model structure. As you can see, it has two sub-models, Informer and LSTM. This repo is about the codes of these two models and experiments we made.

In the project experiment, we combine many data sources into many datasets to test not only the robustness of the model but also the effectiveness of the data sources. By using such an experiment method, we can reduce both the bias and the variance of our model.

For the final artifact, you can find the files and codes:

* dataset: `dataset/bac/8combinations/indi_final_twitter_finbert_avg.csv` , 

* LSTM model:  `lstm/LSTM_indi_final_twitter_finbert_avg_5/LSTM_indi_final_twitter_finbert_avg_5.ipynb`
* Informer model: `Informer/bac_19col_newsent_indi_5@indi_final_twitter_finbert_avg/bac_19col_newsent_indi_5.ipynb`

If you want to repuce the results, be sure the copy the LSTM's predicted results  `indi_final_twitter_finbert_avg.npy` to the Informers folder.

You can also find the prediction plot figures of Ensemble, Informer, Arima (baseline) model in `Informer/bac_19col_newsent_indi_5@indi_final_twitter_finbert_avg/bac_19col_newsent_indi_5.ipynb` and the LSTM's plot figure in `Informer/bac_8col_fbsum_sentiment_3col@finbert_likes_sum_final/informer_bac_8col_fbsum_sentiment_3col.ipynb`
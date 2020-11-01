Engine RPM Profile
==============================

Created by Zichu Li, Yuan Lu, Haoyuan Dong, Chunlei Zhou

This project aims to predict the metric such as HighRPM, MaxRPM and use the metric to better
understand the driver behavior

How to run?
------------

Train the model using default data

    python src/main.py --config train.json

Get the prediction on the unseen data

    python src/main.py --config test.json

How to check result?
------------

Model result will store under the `path_to_save` directory which is default as `./data`

`pooling_result.csv` : result from pooling approach

`summarized_result.csv` : result from summarization approach

`sum_prediction.csv` : result from combined two approaches 


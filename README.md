# sql-xss-CNN
Tập data gồm các payload được thu thập từ:
- https://github.com/client9/libinjection](https://github.com/client9/libinjection
- https://github.com/das-lab/deep-xss](https://github.com/das-lab/deep-xss
- https://github.com/Morzeux/HttpParamsDataset](https://github.com/Morzeux/HttpParamsDataset
- https://petescully.co.uk/research/csic-2010-http-dataset-in-csv-format-for-weka-analysis/ CSIC 2010
- https://www.kaggle.com/syedsaqlainhussain/cross-site-scripting-xss-dataset-for-deep-learning
- Full_dataset: 240666 sample
+ normal: (deepxss+HttpParam+CSIC 2010) 89781
+ sql: (HttpParam+libinjection) 89468
+ xss: (deepxss+libinjection+kaggle) 61418

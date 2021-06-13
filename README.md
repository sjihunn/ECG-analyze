# ECG-analyze
data_preprocessing_example.ipynb 파일과같이 ecg raw file을 전처리해서 v peak을 찾아내고, 마찬가지로 n peak도 찾아 냅니다.
찾을 수 있는 v peak이 한정돼 있으므로, n peak도 v peak에 상응하게 5000개씩 추출했습니다.
이렇게 모은 total_dataset.csv파일을 이용하여 data_train_test.ipynb에서 학습을 시키고 성능을 측정합니다.

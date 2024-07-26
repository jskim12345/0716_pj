데이터 수집 : 캐글 분리수거 데이터
https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2?select=trash

1채널학습(그레이스케일) : 그레이스케일 및 데이터 전처리 후 그레이스케일 학습


sobel(그레이스케일 + 데이터전처리) : 그레이스케일 및 데이터 전처리 후 소블학습


0717 canny : 데이터 전처리 후 캐니학습


resnet18(데이터증강) : resnet18 모델 사용 모델학습 (과적합 및 학습시간이 너무 오래걸려 학습중단)


mobilenet(랜덤서치_시각화) : mobilenet_V2 모델 사용 랜덤서치를 통한 최적의 하이퍼 패러미터 도출


0717 최적의하이퍼파라미터 : 랜덤서치를 통해 도출한 최적의 하이퍼 패러미터 mobilenet_v2모델을 통해 학습


mobilenet(데이터증강) : 데이터증강 전/후 mobilenet_V2 모델 사용 모델학습 & 시각화


efficientnet_b2_랜덤서치 30번 : efficientnet_b2 모델 사용하여 10번학습, 3번 반복


efficientnet_b2_랜덤서치 70번 : efficientnet_b2 모델 사용하여 10번학습, 7번 반복


efficientnet_b2_그리드서치 :  efficientnet_b2 모델 사용후 그리드서치 


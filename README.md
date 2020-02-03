# Amazon SageMaker Studio Hands-on Lab

## Introduction
기계 학습(ML) 모델은 딥러닝 아키텍처와 GPU의 발전으로 최근 몇 년간 매우 빠르게 진보되었지만, 고도화되지 못한 ML 워크플로로 많은 고객들이 production 적용에 많은 어려움을 겪고 있습니다. 최근, re:Invent 2019에서 출시된 통합 ML 개발 환경(IDE)인 Amazon SageMaker Studio를 포함한 신규 서비스들을 통해 최적의 모델을 만들기 위한 수많은 반복 작업을 쉽고 빠르게 수행할 수 있게 되었고, 또한 모델 학습 중이나 모델 배포 이후의 이상점들을 실시간으로 모니터링할 수 있게 되었습니다.

이에, AWS에서는 ML 워크플로를 쉽고 빠르게 구축하고자 하는 데이터 사이언티스트 및 ML 엔지니어 분들을 위해 Amazon SageMaker Studio Hands-on Lab을 준비했습니다. 이 워크샵을 통해 Amazon SageMaker Studio상에서 notebook instance를 생성하고 샘플 Jupyter 노트북을 실습하면서 SageMaker의 기능들을 알아보도록 합니다. 

실습은 총 4개 모듈로 구성되어 있으며, 1번 모듈 완료 후 2번 모듈을 순서대로 진행하셔야 합니다. 3번, 4번 모듈은 원하는 순서대로 진행하실 수 있습니다.


### Requirements 
- AWS Region: **Ohio** (필수)
- Browser: 최신 버전의 **Chrome, Firefox**를 사용하세요.
- 주의 사항: 노트북(Notebook) 안의 Cell에서 코드 실행 후 결과 값이 나오는 데는 수 초가 걸리며, 훈련 Job을 실행하는 경우 수 분에서 수십 분이 걸릴 수도 있습니다. 

## Agenda

### Module 1. Amazon SageMaker Studio
Amazon SageMaker Studio IDE(Integrated Development Environment)를 시작해 봅니다.

### Module 2. Amazon SageMaker Autopilot
탐색적 데이터 분석(EDA), 피쳐 엔지니어링, 파이프라인 추천, 하이퍼파라메터 튜닝을 자동으로 수행하는 완전 관리형 AutoML 서비스인 Amazon SageMaker Autopilot을 사용하여 고객 이탈 예측 모델을 자동으로 생성해 봅니다.
- [Getting Started](autopilot/lab2.md)

### Module 3. Amazon SageMaker Debugger
학습 중 실시간으로 디버그 후크(Debug Hook)로 캡처된 텐서를 분석하고 이상점들을 확인하여 모델의 문제를 감지할 수 있는 Amazon Sagemaker Debugger를 사용하여 손글찌 숫자 인식 모델을 MNIST 데이터셋과 TensorFlow로 학습해 봅니다.
- [Getting Started](debugger/lab3.md)

### Module 4. Amazon SageMaker Model Monitor
모델 배포 이후 데이터 드리프트, 휴먼 에러 등으로 인해 데이터 품질이 변하는 것을 실시간으로 모니터링하는 SageMaker Model Monitor 서비스를 사전 학습된 고객 이탈 예측 모델에 대해 실습해 봅니다.
- [Getting Started](model-monitor/SageMaker-ModelMonitoring.ipynb)

## License Summary
이 샘플 코드는 MIT-0 라이센스에 따라 제공됩니다. LICENSE 파일을 참조하십시오.
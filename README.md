# MLOps_study
## MLflow

1. Core components of mlflow
    
    DS 프로젝트의 사이클
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/70275f66-444c-41c9-81d7-50304dada995/b0204a1b-c2ca-4495-8809-6f3777e647da/image.png)
    
    1. Data Preparation
    - ETL 파이프라인, DB에서 데이터 가져오기
    1. EDA
    2. Feature Engineering
        1. 카테고리, 실수형 피처 구분 등등
    3. Model training 
    4. Model Validation
    5. Deployment
    6. Monitoring
        1. 모델이 재학습이 필요한지
2. why use mlflow
3. who uses mlflow
4. usecase of mlflow

데이터 사이언티스트가 mlflow를 이용하는 방법

1. 실험을 트래킹하고 가정을 실험
2. 코드 스트럭처링 ( 파이프라인 만드는 과정 )
3. 모델 패키징과 의존성 관리(setup.py)
4. 하이퍼파라미터 평가하기 ** 핵심기능
    1. 모든 하이퍼파라미터 tuning시 tracking 가능
    2. 파라미터별 시각화도 해둠
5. 모델의 (재)학습 결과들을 비교함 → 최적 모델 선택

MLOPS 전문가가 mlflow를 사용하는 법

1. 모델 학습 life cycle 관리, 모델 배포
2. 보안상 안전하게 모델 배포하기
3. 배포 의존성 관리하기

Prompt Engineering 유저

1. LLM 평가, 실험 
2. 커스텀 프롬프트 만들기 , 실험
3. 최고의 모델 선택하기

Usecase

1. 실험 트랙킹 ( 파라미터, 매트릭) → UI로
2. 모델 선택과 배포
3. 모델 성능 모니터링
4. 협동 프로젝트에서 유용

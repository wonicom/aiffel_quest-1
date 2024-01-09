# AIFFEL Campus Online 7th Code Peer Review Templete

- 코더 : 윤여원
- 리뷰어 : 김찬중



🔑 **PRT(Peer Review Template)**

- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부
     
        - KITTI 데이터셋 구성, U-Net 모델 훈련, 결과물 시각화의 한 사이클이 정상 수행되어 세그멘테이션 결과 이미지를 제출하였습니다.
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/945ec756-f916-4ab9-9e55-8a4de8df692a)
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/058e903e-f3ec-4771-8d51-92524dc72089)

        - U-Net++ 모델을 스스로 구현하여 학습 진행 후 세그멘테이션 결과까지 정상 진행되었습니다.
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/41bb3eb5-580e-4b0f-bd51-3c937351dde9)
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/d9834595-fe39-4ab7-ab9d-51bd2f279af1)

        - U-Net++ 의 세그멘테이션 결과 사진과 IoU 계산치를 U-Net과 비교하여 우월함을 확인하였습니다.
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/136926d4-7851-4a18-a36a-901f5e52a8c2)

          
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
     
        - 주석을 통해 코드에 대해 쉽게 이해 할 수 있었습니다.
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/1f3c10c0-22ad-49d7-a84a-9780ee02d9e1)

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인 또는
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
     
        - 깃 허브에 있는 xnet과 backbone을 도입하여 코드 구현을 시도 하였습니다.     
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/3109d0e1-6194-47c1-b5e8-794e1620e2d3)

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 상세히 기록되어 있는지 확인
        - 딥러닝 모델의 경우,
        인풋이 들어가 최종적으로 아웃풋이 나오기까지의 전체 흐름을 도식화하여 
        모델 아키텍쳐에 대한 이해를 돕고 있는지 확인

        - 회고를 통해 느낀점과 아쉬운점 그리고 앞으로 학습 방향에 대해 잘 나타내었습니다.
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/02e3c4d5-7939-479a-91b1-7ddf2de99d46)



- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 모듈화(함수화) 했는지
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
     
        - 함수화를 통해 코드를 간결하고 가독성 있게 잘 작성하였습니다.
        - ![image](https://github.com/kcj4800/aiffel_quest_yw/assets/128466813/d7133cb6-e668-4a66-ab7b-ce814816ba47)

### 전체적으로 여러가지 복잡한 시도들을 통해 코드를 구현하고자 노력하였고, 이러한 도전정신이 빛나는 코드였습니다. 항상 모든일에 주저없이 도전하시는 모습이 아이펠에서 가장 강조하는 러닝 바이 두잉의 자세가 아닐까 생각합니다. 앞으로도 그런 모습 기대하며, 쭉쭉 성장하시길 바라겠습니다. 불타는 토마토 윤여원 파이팅!


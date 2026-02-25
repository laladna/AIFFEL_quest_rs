# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 금동연
- 리뷰어 : 정정채


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 모델 학습은 현재 진행 중이며, 최종 성능을 확인하기 위해 추가 시간이 필요한 상황임
    - 설정한 목표 점수(90점)는 아직 달성되지 않았으나, 지속적인 학습과 튜닝을 통해 개선 가능성이 충분히 있어 보임
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    
    - EDA 분석을 통해 Truncation 임계치를 조절하는 개선사항을 도출하는 과정이 매우 인상깊었음
    - 해당 부분에 주석 및 설명이 자세히 적혀있어 이해하기 쉬웠음  
      <img width="791" height="406" alt="image" src="https://github.com/user-attachments/assets/9d705d71-eb78-4f80-8cbd-a7d559490cf3" />  
      <img width="707" height="393" alt="image" src="https://github.com/user-attachments/assets/2feb579d-446f-4933-ba6a-31fce3ec7902" />
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - EDA 결과를 토대 학습 전략을 재설계함
    - Pedestrian와 같은 희소 클래스 학습 기회를 증가시키기 위한 방법을 씀
    - 학습 속도 개선을 위해 설정을 재조정함  
      <img width="604" height="135" alt="image" src="https://github.com/user-attachments/assets/25a22742-388d-44f5-a6d8-c77a4a8f099f" />

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 프로젝트가 현재 진행 중이므로 최종 회고는 아직 작성하지 못함
    - 그러나 중간 과정에서 수행한 EDA 분석을 통해 데이터 난이도 분포와 클래스 불균형 문제를 인지하여 이를 기반으로 학습 전략을 수정한 점이 인상 깊었음
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 추가 및 수정할 코드에 대한 설명이 자세히 되어 있어서 이해하기 쉬웠음  
      <img width="590" height="110" alt="image" src="https://github.com/user-attachments/assets/6235b1c6-448f-45b5-8157-822a058457af" />
      <img width="456" height="51" alt="image" src="https://github.com/user-attachments/assets/2ec9a90f-3007-4900-a5ff-15c6bd53d865" />



# 회고(참고 링크 및 코드 개선)
- 모델 학습 전에 데이터 분포를 충분히 이해한 후 학습을 진행한 점이 인상적이었습니다.
- 직관적인 추측에 의존하지 않고, EDA 결과를 근거로 설정값과 학습 전략을 재조정하는 등의 개선 방향을 도출한 과정이 인상 깊었음


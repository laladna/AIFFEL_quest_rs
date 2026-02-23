# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정정채
- 리뷰어 : 금동연


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제 해결을 위한 코드가 잘 제출됨
    - 프로젝트에서 요구하는 과제를 잘 수행
      <img width="402" height="114" alt="image" src="https://github.com/user-attachments/assets/1d27f5c9-9810-4287-bc62-6c26ed9b0d8b" />  
      <img width="802" height="403" alt="image" src="https://github.com/user-attachments/assets/b90e2272-25a3-4ebe-93dc-df97afd45e39" />

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 코드에 대한 설명 및 회고가 잘 작성되어 이해하기 쉬웠음  
      <img width="583" height="259" alt="image" src="https://github.com/user-attachments/assets/1cb099e0-f46c-48c6-a669-ae279709ac2b" />

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 실험 소요시간 및 환경에 대한 제한으로 여러 설정을 적용하여 실험을 원활히 함
      - Scheduler 설정  
        <img width="783" height="127" alt="image" src="https://github.com/user-attachments/assets/3206caf3-7186-4243-afff-bd0fdeb7c3b2" />
      - 데이터셋 크기 조절  
        <img width="448" height="79" alt="image" src="https://github.com/user-attachments/assets/907548ba-0709-4ee6-be3e-72678cfa5d85" />

    - 논문을 기반으로 Bias 값의 유무에 따른 차이를 검증하고 실험을 진행한 것이 인상적이었음
      - Bias 값의 유무에 따른 분류 정확도 차이 검증
      - Bias 값의 유무에 따른 CAM, Grad-CAM 간 IOU 차이  
        <img width="786" height="260" alt="image" src="https://github.com/user-attachments/assets/126da5ac-fd5c-48de-aa69-173035aac139" />
        
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 추가 실험에 대한 결론을 구체적으로 작성하여 어떤 결과가 도출되었는지 정확히 알 수 있었음  
      <img width="759" height="327" alt="image" src="https://github.com/user-attachments/assets/2fc4bc03-ad0a-4995-b620-fbbc5b8460eb" />
    - 실험에 대한 회고를 작성하여 어떤 고민과 실험이 있었는지 명확히 알 수 있었음
    - 향후 어떤 개선사항과 궁금증이 있었는지 제시해주어 같이 고민할 수 있는 기회가 되어 좋았음  
      <img width="764" height="339" alt="image" src="https://github.com/user-attachments/assets/71475a05-9d6e-4f19-9f44-e70bb5d9e8ed" />
      
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 코드의 스타일을 일관성 있게 잘 작성하여서 코드를 이해하는 데에 불편함이 없었음
    - 코드에 대한 주석 및 설명을 구체적으로 작성하여 어렵지 않게 이해할 수 있었음
    - 평균 IOU 계산, 그래프 생성 등 반복적인 작업을 함수로 작성하여 간결함을 높였음  
      <img width="592" height="588" alt="image" src="https://github.com/user-attachments/assets/2327f165-5099-475e-9033-e423f0df6ef7" />


      


# 회고(참고 링크 및 코드 개선)
- 관련 논문을 검토하고 이를 기반으로 실험 주제를 도출한 점이 매우 인상적이었습니다. 그 결과,  연구의 방향성과 근거가 명확하게 제시되어 실험 설계의 타당성이 잘 드러났던 것 같습니다.
- 실험 결과를 효과적으로 해석하기 위해 다양한 그래프와 시각화 자료를 활용한 점이 돋보였습니다. 이를 통해 결과에 대한 이해도를 높이고, 분석 내용을 직관적으로 이해할 수 있었습니다.
- 실험 과정에서 발생한 제약 사항을 극복하기 위해 다양한 설정을 조정하며 문제를 해결하려는 시도가 인상적이었다. 이러한 접근 방식으로 실험의 완성도가 높아지고 원활한 실험을 진행하실 수 있었던 것 같습니다.

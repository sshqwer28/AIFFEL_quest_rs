# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 채세현
- 리뷰어 : 신대웅


# PRT(Peer Review Template)
- [V]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 각각 모델에 대한 평가지표를 출력하도록 완성된 코드를 제출하였으며, 결과를 바탕으로 의미있는 분석을 도출하였음 
<img width="755" height="226" alt="image" src="https://github.com/user-attachments/assets/4fc9b79f-92f4-4841-a613-f4a11e982411" />

    
- [V]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - BLEU, ROUGE, Perplexity 등의 정량적인 평가와 LLM-as-a-Judge 프롬프트라는 정성적인 평가를 도입하여 적용한 해당 코드가 이 모델의 가장 핵심 부분이라고 판단됨
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 주석을 통하여 기술
<img width="851" height="699" alt="image" src="https://github.com/user-attachments/assets/4510ae5f-8eab-4d4d-9ce4-655cea290d32" />

        
- [V]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 정량적 평가에 추가하여 정성적인 평가를 통하여 Baseline, SFT, RM Model의 출력 결과를 다양한 측면에서 평가하고자 하는 시도를 하였음
<img width="856" height="627" alt="image" src="https://github.com/user-attachments/assets/f84a2c0d-6dad-4fc3-9df3-0f8827a4ad39" />

        
- [V]  **4. 회고를 잘 작성했나요?**
    - 회고를 통하여 아쉬운 점과 보완이 필요하다고 생각되는 점을 파악한 부분이 두드러지며 평가 체계의 다각화에 대해 고민해보았다는 점에서 이번 실험이 코드에게 의미가 있었을 것으로 판단됨
<img width="786" height="531" alt="image" src="https://github.com/user-attachments/assets/bcd7dfde-ddbe-47e1-be1b-1915d3b55392" />

        
- [V]  **5. 코드가 간결하고 효율적인가요?**
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화 및 모듈화하였음
    - 코드가 간결하고 노드의 학습 순서에 따라 효율적으로 설계되었음
<img width="839" height="751" alt="image" src="https://github.com/user-attachments/assets/f8ec9cbf-b3ef-4fb5-aab1-6b7c1feeea78" />


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어와 다르게 정성적인 결과가 두드러지게 개선되었다는 점에서 전체적인 모델 설계에 오류가 없음을 보여주었음
# LLM-as-a-Judge 방식을 어떻게 적용하는지 배울수 있어서 좋았음
# 코더의 의견과 같이 RAG 기술을 결합한다면 더 품질 높은 모델이 구현될 수 있을 것으로 예상됨
```

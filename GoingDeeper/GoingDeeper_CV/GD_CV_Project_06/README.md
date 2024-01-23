# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김찬중
- 리뷰어 : 이승제


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 퀘스트 문제 요구조건 등을 지칭
     
    - 텍스트 이미지 리사이징, ctc loss 측정을 위한 라벨 인코딩, 배치처리 등이 적절히 수행되었다.
     
    ![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/85f70835-af67-4842-a9fa-c2bf4a56ee09)
    
    ![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/86cdee80-ca1b-4ea2-a605-42f42dac6521)


    -> 해당 함수를 사용하여 데이터 처리를 잘 했다.


    - 학습결과 loss가 안정적으로 감소하고 대부분의 문자인식 추론 결과가 정확하다.

    ![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/071098ac-91e0-4e99-9c76-a881c0e42849)

![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/b0e70a81-2d8b-49ee-881d-428d402efbb9)


    - 샘플 이미지를 원본으로 받아 OCR 수행 결과를 리턴하는 1개의 함수가 만들어졌다

![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/b3d7567d-9e19-4d3f-8dd7-cf69cd33bfda)

    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
     
![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/f0cca1e4-2258-46f6-8ba1-ae7cadd6812d)

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인

![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/3e1d7c11-35bb-4f3f-8807-9b91d2ed9dd1)

![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/f822fc26-f1ee-4699-9cc8-5afbd95cda22)


-> 노드와 다르게 epoch수를 다르게 실험하였고 프로젝트 함수를 잘 처리한 흔적이 보인다. 
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
     
![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/9f5388d2-a9bc-43ea-8ca1-6770fcddd3f7)

- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지

![image](https://github.com/kcj4800/Aiffel_Quest/assets/85716670/88811a16-3f6a-4218-9cb9-b5d781bbef5c)

-> history를 저장하는 함수가 잘 짜여 있어 간결하다.

# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```


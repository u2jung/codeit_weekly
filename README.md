# codeit_weekly
---

## weekly_1


### Q. 1종 오류와 2종 오류 
- 1종 오류와 2종 오류는 통계적 가설검정 과정에서  발생할 수 있는 두 가지 유형
- 통계적 가설검정에서 귀무가설(null hypothesis)과 대립가설(alternative hypothesis)을 검증할때 발생
 > 귀무가설 : 아무일도 일어나지 않았음을 가정하는 가설

#### 1종 오류의 정의와 예
- 귀무가설이 참일때, 귀무가설을 기각하는 오류
- **실제로는 차이가 없는데 차이가 있다고 잘못 판단하는 경우**
- 알파 오류, False Alarm
 - 예시 어떤 약의 효과에 대한 실험 -> 귀무가설 '이 약은 효과 없다', 대립가설 ' 이 약은 효과가 있다' -> 실험 결과 : 약은 효과가 있다고 판단, 귀무가설 기각 -> 그러나 실제로 이 약은 효과가 없음, 실험결과에 오류가 있어 잘못판단 -> 1종 오류 발생


#### 2종 오류의 정의와 예
- 귀무가설이 거짓일때, 귀무가설을 채택하는 오류
- **실제로는 차이가 있는데 차이가 없다고 잘못 판단하는 경우**
- 베타 오류, False Negative
   - 예시 어떤 약의 효과에 대한 실험 -> 귀무가설 '이 약은 효과 없다', 대립가설 ' 이 약은 효과가 있다' -> 실험 결과 : 약은 효과가 없다고 판단, 귀무가설 채택 -> 그러나 실제로 이 약은 효과가 있음, 실험결과에 오류가 있어 잘못판단 -> 2종 오류 발생

 -> 1종 오류와 2종 오류는 서로 상반된 관계, 연구의 목저고가 상황에 따라 적절한 수준의 1종 오류와 2종 오류를 고려하여 검증과정을 설계


 #### 오류 최소화
 - 1종 오류 : 실제 차이가 없으나 있다고 판단 > 엄격한 검증 기준 적용
 - 2종 오류 : 실제 차이가 있으나 없다고 판다 > 완화된 검증 기준 적용
  - 적절한 표본을 선택하여 검증의 정확성 높이기
  - 검증기준을 잘 설정하여 오류 간의 균형 맞추기
  - 여러가지 검증 방법을 동시에 사용

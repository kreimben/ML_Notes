# AI를 이용한 주식 가치평가 2팀

## Python
[python 3.7 32bit download here.](https://www.python.org/downloads/release/python-379/)

## 실행
**가상환경을 새로 만들어 이용하세요.**
* ~~`venv37_32`는 대신증권 API로 부터 주가 데이터를 얻어오는데 씁니다.~~
* ~~`venv310_64`는 일반적인 데이터 분석-머신러닝을 프로그래밍 하는데 씁니다.~~
* `venv` 디렉토리 생성 후 가상환경 설치, [`requirements.txt`]('./requirements.txt')로 패키지 설치하세요.

---

### 이 프로젝트는 PyCharm을 이용해 구현하였습니다. 동일한 결과를 얻고 싶다면 다음과 같은 환경을 설정해주세요.
* IDE: PyCharm
* Python: ~~3.7 32bit,~~ 3.10 64bit
* PyPi: [requirements.txt](./requirements.txt)
* Data Source: ~~대신증권 API~~ Yahoo Finance.

---

## 구현 현황

- [x] `requirements.txt` 준비.
- [ ] ~~대신증권 API 이용해 증권 데이터 가져오기.~~
- [x] 야후 파이낸스를 이용해 증권 데이터 가져오기.
- [x] 주식 비교하기
- [x] 최대 손실 낙폭
- [x] 회귀 분석과 상관관계
- [x] 상관계수에 따른 리스크 완화
- [x] 현대 포트폴리오 이론
- [x] 샤프 지수와 포트폴리오 최적화
- [x] 볼린저 밴드 지표
- [x] 볼린저 밴드 매매기법
- [x] 심리투자 법칙
- [x] 삼중창 매매 시스템
- [x] 듀얼 모멘텀 투자
- [ ] 백트레이더를 활용한 백테스트
- [ ] 변동성 돌파 전략
- [ ] 텐서플로 선형 회귀 문제
- [ ] 텐서플로 RNN을 이용한 주가 예측
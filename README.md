# javascript-lotto-precourse

# 기능 요구사항
1. **로또 발행 기능**
    - 중복되지 않는 6개의 숫자(숫자 범위는 1~45)를 뽑기

2. **로또 추첨 기능**
    - 중복되지 않는 숫자(숫자 범위는 1~45) 6개와 보너스 번호 1개를 입력

3. **당첨 통계 기능**
    - 당첨된 1등부터 5등까지 통계를 계산
        - 1등: 6개 번호 일치 / 2,000,000,000원
        - 2등: 5개 번호 + 보너스 번호 일치 / 30,000,000원
        - 3등: 5개 번호 일치 / 1,500,000원
        - 4등: 4개 번호 일치 / 50,000원
        - 5등: 3개 번호 일치 / 5,000원
        - 총 수익률 계산

4. **로또 게임 기능**
    - 로또 구입 금액을 입력하면 구입 금액에 해당하는 만큼 로또를 발행(로또 1장의 가격은 1,000원)
    - 당첨 번호와 보너스 번호 입력
    - 사용자가 구매한 로또 번호와 당첨 번호를 비교하여 당첨 내역 및 수익률을 출력하고 로또 게임을 종료
        - 사용자가 잘못된 값을 입력할 경우 "[ERROR]"로 시작하는 메시지와 함께 Error를 발생시키고 해당 메시지를 출력한 다음 해당 지점부터 다시 입력

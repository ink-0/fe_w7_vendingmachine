# 🔥Feature List

## 1️⃣ node, express 설정  
## 2️⃣ html css 구조 짜기 
## 3️⃣ model 객체 ( 지갑, 상품정보 ),  view객체(진행화면)

## 4️⃣ 동작 구현  

- [ ] `지갑화면`( 동전 누르기) -> `진행화면` (동전 금액 표시) ,`지갑화면`(동전갯수 ,총액변경)    
<br>
>  상품 선택할 경우 (돈투입 5초마다 입력 확인)
- [ ] 투입된 금액 충족 -> `상품화면` (<u>구매할 수 있는 상품</u>_(총액<=상품가격)_ 표시)
상품선택 -> 2초 뒤 `진행화면`('바나나 우유'가 선택됨)

<br>

> 상품 선택 안할 경우
- [ ] 돈투입후 5초마다 입력 확인 -> `진행화면` (잔돈 '500원'반환) -> `지갑화면` (잔돈 채워짐)

<br>

- [ ] 재고 관리(local storage?)
- 자판기 내부에서 관리
- (재고>0)일 때 만 <u>구매할 수 있는 상품</u>에 표시
  
<br>

## ❖ 주의사항
* 모든 이벤트 진행화면(메세지창)표시
* 5초마다 동전 입력 
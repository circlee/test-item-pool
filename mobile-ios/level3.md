
# 시작하기
- macOS - Command Line Tool 템플릿으로 시작하세요.
- 아래 요구사항을 만족하는 앱을 완성하세요.
- 본인 github에 저장소를 새로 만들고 문제 해결 과정을 단계별로 커밋 메시지에 기록하세요.

###  요구사항#1. 아래 상품을 추상화한 클래스 만드세요
- 속성에 따라 상위, 하위 부류를 만들어 상속관계를 만드세요.
	- (자기만의 기준으로) 클래스 이름을 정하세요.
- 필수 속성 : 브랜드(String), 무게(Int), 가격(Int), 이름(String), 제조일자(Date)
- 상품 클래스에 비교를 위해서 Protocol Equatable 을 추가하고 구현하세요.

### 요구사항#2.  5가지 종류 상품을 판매하는 자판기 struct를 만드세요
다음과 같은 동작을 위한 함수를 작성하세요.
- 자판기 금액을 원하는 금액만큼 올리는 함수
- 특정 상품 인스턴스를 넘겨서 재고를 추가하는 함수
- 현재 금액으로 구매가능한 상품 목록을 리턴하는 함수
- 특정 상품를 구매하는 함수
- 잔액을 확인하는 함수
- 전체 상품 재고를 (사전으로 표현하는) 종류별로 리턴하는 함수
- 시작이후 구매 상품 이력을 배열로 리턴하는 함수

### 요구사항#3.  main에서 메뉴를 구성하세요.
- 자판기 화면을 자기만의 방식으로 메뉴를 표시하세요.
- 메뉴에서 입력하는 동작을 자판기 함수에 연결하세요.
- 전체 코드를 확인할 수 있는 통합 테스트 시나리오를 가지고 동작을 확인하세요.
	- 예를 들어서, 재고 몇 개 추가하고 잔액 얼마 추가하면 어떤 상품 구매가능, 불가능인지 확인하고 가능한 상품 구매하고, 잔액 바뀌고 재고 상태 바뀌고, 구매 상품 이력을 확인한다.
- [ANSI Escape Code](https://en.wikipedia.org/wiki/ANSI_escape_code)를 활용해서 화면을 꾸며보세요.
- 아래 ANSI 관련 코드를 받아서 확장해도 됩니다.
https://www.dropbox.com/s/gwho0rrelfsrc06/HelloSwift.zip?dl=0
	- 화면 예시
	![콘솔 메뉴](http://public.codesquad.kr/jk/level2-console-menu.png)


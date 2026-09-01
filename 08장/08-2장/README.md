[⬆ 08장로 돌아가기](../README.md)

# 08-2장 - 생성자 호출 순서와 다단계 상속

TV → wideTV → SmartTV로 이어지는 다단계 상속 구조에서 파생 클래스 객체 생성 시 각 생성자가 어떤 순서로 호출되고 인수가 어떻게 전달되는지를 분석하고, 생성자와 멤버변수 설정 함수를 추가해 실행 결과를 재현하는 실습입니다(실습과제1~2). 이어서 Circle 클래스를 상속받는 NamedCircle 클래스를 작성해 이름 속성을 추가하고, 배열로 여러 객체를 다루는 문제도 포함합니다(418~424페이지 문제).

## 실습과제

<details>
<summary>418~424페이지2문제 / 1번</summary>

위치와 반지름을 가진 Circle 클래스를 상속받아 이름(name) 속성을 추가한 NamedCircle 클래스를 작성해, 이름이 있는 원 객체를 만들고 출력하는 실습입니다.

📁 [해당 폴더로 이동](./418~424페이지2문제/1번/)

</details>

<details>
<summary>418~424페이지2문제 / 2번</summary>

1번의 NamedCircle 클래스를 이용해 여러 개의 NamedCircle 객체를 배열로 선언하고, 배열을 순회하며 각 원의 이름과 정보를 출력하는 main 함수를 작성하는 실습입니다.

📁 [해당 폴더로 이동](./418~424페이지2문제/2번/)

</details>

<details>
<summary>실습과제1</summary>

TV → WideTV → SmartTV로 이어지는 다단계 상속 구조에서, SmartTV 객체 생성 시 SmartTV 생성자가 WideTV(size, videoIn) 생성자를 호출하고, WideTV 생성자는 다시 TV(size) 생성자를 호출하는 식으로 생성자가 상위 클래스부터 순서대로 호출되며 인수가 전달되는 과정을 분석해 서술하는 문제입니다.

📁 [해당 폴더로 이동](./실습과제1/)

</details>

<details>
<summary>실습과제2</summary>

TV(크기)·WideTV(와이드 여부)·SmartTV(IP 주소)에 각각 생성자와 멤버변수 설정 함수를 추가해, 세 단계 상속 구조를 가진 SmartTV 객체가 실행 결과와 같이 동작하도록 완성하는 실습입니다.

📁 [해당 폴더로 이동](./실습과제2/)

</details>

<details>
<summary>실습과제3</summary>

08-1장의 Shape/Circle/Rect/Triangle 상속 구조를 응용해 추가 조건에 맞게 클래스를 보완하는 실습입니다.

📁 [해당 폴더로 이동](./실습과제3/)

</details>

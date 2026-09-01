[⬆ 08장로 돌아가기](../README.md)

# 08-1장 - 상속과 접근 지정자

위치좌표(x, y)를 멤버로 갖는 Shape 클래스를 만들고 이를 상속하는 Circle·Rect·Triangle 파생 클래스를 작성하는 실습입니다. 실습과제1에서는 x, y를 private으로, 실습과제2에서는 protected로 선언해 접근 지정자에 따라 파생 클래스에서의 접근 가능 여부가 어떻게 달라지는지를 비교합니다.

## 실습과제

<details>
<summary>실습과제1</summary>

위치좌표(x, y)를 private 멤버로 갖는 Shape 클래스를 만들고, 이를 상속하는 Circle(반지름)·Rect(너비, 높이)·Triangle(밑변, 높이) 세 파생 클래스를 각각 정의해 좌표와 도형별 속성을 함께 출력하도록 구현합니다.

📁 [해당 폴더로 이동](./실습과제1/)

</details>

<details>
<summary>실습과제2</summary>

실습과제1과 같은 Shape/Circle/Rect/Triangle 구조를, 이번에는 Shape의 x, y 멤버를 private 대신 protected로 선언해 파생 클래스에서 부모의 좌표 멤버에 직접 접근할 수 있도록 구현합니다.

📁 [해당 폴더로 이동](./실습과제2/)

</details>

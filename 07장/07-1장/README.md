[⬆ 07장로 돌아가기](../README.md)

# 07-1장 - 프렌드/멤버함수로 연산자 구현하기

실수부(rPart)·허수부(iPart)를 멤버로 갖는 Complex 클래스를 만들고, 두 복소수를 더하는 기능을 전역함수(ComplexAdd) → ComplexManager 클래스의 멤버함수 → ComplexAdd/ComplexSub 두 개의 멤버함수로 단계적으로 옮겨가며 구현하는 실습입니다.

## 실습과제

<details>
<summary>실습과제1</summary>

실수부(real)·허수부(img)를 private 멤버로 갖는 Complex 클래스를 만들고, 두 Complex 객체를 더하는 Complexadd를 클래스 외부의 전역함수로 선언한 뒤 friend로 등록해 private 멤버에 접근할 수 있게 구현합니다.

📁 [해당 폴더로 이동](./실습과제1/)

</details>

<details>
<summary>실습과제2</summary>

실습과제1의 덧셈 기능을 전역함수 대신 별도의 ComplexManager 클래스의 멤버함수 ComplexAdd로 옮겨 구현하고, Complex 클래스에서는 이 멤버함수만 friend로 선언해 접근을 허용합니다.

📁 [해당 폴더로 이동](./실습과제2/)

</details>

<details>
<summary>실습과제3</summary>

ComplexManager 클래스에 ComplexAdd에 이어 ComplexSub(뺄셈) 멤버함수를 추가하고, Complex 클래스 전체를 ComplexManager의 friend 클래스로 선언해 ComplexManager의 모든 멤버함수가 Complex의 private 멤버에 접근할 수 있도록 구현합니다.

📁 [해당 폴더로 이동](./실습과제3/)

</details>

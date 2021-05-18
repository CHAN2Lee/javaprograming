## Do it 자바 프로그래밍 정리

- 프로그래밍이란 컴퓨터에게 일을 하도록 명령어를 만드는 것을 칭한다.
- 컴파일: 프로그램 언어를 컴퓨터가 알 수 있는 언어로 바꿔 주는 일
- 컴파일러: 기계어로 번역해주는 프로그램, 자바를 설치하면 자바 컴파일러 또한 설치 된다.

## HelloWorld 출력하기

- first 패키지의 HelloWorld 클래스 생성

 package first;

 public class HelloWorld {

   public static void main(String{} args){
       System.out.println("Hello, World");

    }
}

## 변수와 자료형

- 숫자를 10진수와 8진수, 16진수로 표현 하는법

package chapter2
public class BinaryTest{
    public static void mian(String[] args){

      int num = 10; // 10진수
      int bNum = 0B1010; // 2진수
      int oNum = 012; // 8진수
      int hNum = 0XA; // 16진수

      System.out.println(num); // 10
      System.out.println(bNum); // 10
      System.out.println(oNum); // 10
      System.out.println(hNum); // 10

    }
}

- 음의 정수를 표현하는 방법은 
  가장 왼쪽에 존재하는 부호 비트를 확인한다.
  MSB(Most Significant Bit)
- 음수를 만드는 방법은 그 수에대한 2의 보수를 취함.

 ## 변수와 자료형

 - 프로그래밍에서 값을 사용하기 위해 선언하는 것을 변수하고 함.
 
 - 변수의 이름은 알파벳과 숫자,_,$로 구성됨.
   
   대소문자를 구분한다.
   
   변수의 이름은 숫자로 시작할 수 없고, 키워드도 변수의 이름으로 사용불가
   
   이름사이에 공백이 있을 수 없다.
   
   * 변수의 이름을 정할 때는 변수의 역할에 어울리는 의미있는 이름으로 지어야 한다.

 - 자료형에는 정수형과 문자형, 실수형, 논리형이 존재한다.

 - 바이트 크기별로 나누어진 byte(1) short(2) int(4) long(8)이 정수형
   문자형인 char(2) 실수형인 float(4), double(8) 마지막으로 논리형인
   boolean(1) //()는 바이트의 수를 나타냄.
 
 
# 2주차: 2부 C# 프로그래밍 (126p - 217p)
	## 4장 C# 프로그래밍 시작하기
	## 5장 게임 오브잭트 제어하
	## 과제
		1. 4장, 5장의 예제 스크립트를 작성하고 github에 pull request로 제출
		2. 4장 내용 중 자신이 기존에 배웠던 언어와 차이점이 뭔지 찾아서 정리하기
		3. 객체지향에 대한 이해도 정리

# 과제2
## 4장 내용 중 자신이 기존에 배웠던 언어와 차이점이 뭔지 찾아서 정리하기

bool
- C#의 bool 자료형은 .NET System 속에 구조체 형식으로 정의되어 있어 다른 함수의 추가 없이 사용 가능하다.
	C의 bool 자료형은 따로 정의되어 있지 않기 때문에 stdbool.h 헤더 파일을 추가하여 사용해야 한다.
- C#의 bool 자료형은 true, false 외 다른 값으로 초기화 할 수 없다.
	C의 bool 자료형은 true, false 외에도 char, int 형 값으로 초기화 가능하다.
    

string
- 객체지향 언어인 C#의 문자열은 클래스이며 이 String 클래스는 Char 객체의 연속으로 이루어져 있다. 문자열은 null-terminating char로 끝나지 않는다.
	C#과 달리 C의 문자열은 Unicode char 값의 연속으로 배열로 이루어져 있다.
    문자열은 null-terminating char로 끝난다.
    
배열(Array)
- C#에서의 배열 선언: int[] arrayName = new int[5];


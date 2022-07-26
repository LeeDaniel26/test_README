# 1주차: 1부 유니티 준비하기 (32p - 123p)
    ## 1장 유니티 준비하기
    ## 2장 유니티 인터페이스 둘러보기
    ## 3장 유니티 엔진이 동작하는 원리
    ## 과제
        1. 2장 중심으로 실제 유니티를 설치하고 사용하면서 영상을 제작해서 올려보기
        2. 3장에서 논의하고 싶은 부분 1개 이상 작성하고 서로 얘기하고 이해하는 시간


# 요약 및 정리
- 1장 유니티 준비하기
	
	유니티 장점:
	- 대부분 기능이 개인 개발자에게 무료
	- 현제 가장 많이 사용하는 엔진. 한국어, 영어 자료가 풍부하다.
	- 멀티 플렛폼 빌드 가능

	게임 개발 입문에 유니티를 추천하는 이유:
	- 유니티는 게임 오브젝트를 미리 만들고 그 오브젝트를 제어하기 위해 코드를 작성한다. 즉, 게임을 개발할 때 바닥부터 코딩을 할 필요가 없어서 뛰어난 프로그래머가 아니어도 쉽게 개발할 수 있다.

	### 유니티 구성
	- Hierarchy\
		현재 씬(Scene)에있는 게임 오브젝트를 표시한다.
	- Inspector\
		게임 오브젝트의 정보와 컴포넌트를 보여준다

	### 컴포넌트 종류
	- 트랜스폼 (Transform)\
		오브젝트의 3차원 좌표와 크기, 회전을 지정합니다.
	- 메시 필터 (Mesh Filter)\
    	3D 메시 파일을 받아 오브젝트의 외곽선을 지정합니다.
	- 메시 렌더러 (Mesh Renderer)\
    	메시를 따라 색을 채워 그래픽 외형을 그립니다.
	- 박스 콜라이더 (Box Collider)\
    	다른 물체가 부딪칠 수 있는 물리적인 표면을 만듭니다.
	- Rigidbody\
    	게임 오브젝트가 물리와 중력의 영향을 받게 함.

- 2장 유니티 인터페이스 둘러보기

	씬 편집 툴:

	**핸드 (Hand) 툴** : 씬 카메라를 움직입니다.\
	**평행이동 (Translate) 툴** : 오브젝트를 이동시킵니다.\
	**회전 (Rotate) 툴** : 오브젝트를 회전시킵니다.\
	**스케일 (Scale) 툴** : 오브젝트의 크기를 조정합니다.\
	**렉트 (Rect) 툴** : UI와 2D 오브젝트의 크기를 조정합니다.\
	**트랜스폼 (Transform) 툴** : 평행이동, 회전, 스케일 툴을 하나로 합친 툴입니다.

	- 커스텀 툴\
		개발자가 원하는 기능을 직접 구현하여 할당할 수 있는 버튼. 현재 선택한 오브넥트에 따라 다른 버튼을 지정할 수 있다.


	핸드 툴로 씬 카메라 이동:
	- Flythrough 모드\
		오른쪽 마우스를 누르는 동안 FPS 게임을 하듯 움직일 수 있다.
	- 궤도(Orbit) 모드\
    	(Windows: Alt+left-mouse, Mac: cmd+left-mouse)\
		씬 중심을 기준으로 회전.\
		궤도모드에서 right-mouse를 사용하면 zoom-in/zoom-out 할 수 있다.


	평행이동 툴:
	- 평행이동 툴의 면을 드래그\
		한 축을 고정시키고 다른 두 축을 움직임.

			**빨간색** : X축(오른쪽)\
			**초록색** : Y축(위쪽)\
			**파란색** : Z축(앞쪽)

	회전 툴:

			**빨간색** : X축(앞뒤로 고개를 숙이고 젖히는 회전)\
			**초록색** : Y축(제자리에서 팽이처럼 도는 회전)\
			**파란색** : Z축(오뚝이처럼 좌우로 기울어지는 회전)

	랙트 툴:\
		주로 UI와 2D 오브텍느를 편집할 때 사용.3D 오브젝트를 편집할 때는 거의 사용하지 않음. 랙트 툴로 3D 오브젝트를 편집하면 Z축 방향을 무시하고 가로(X), 세로(Y) 길이만 조정됨.

	- Gizmo란 씬 창에서 오브젝트 위에 표시되는 아이콘, 편집 툴의 모습(화살표), 외곽선 등을 가리킨다. 씬 창에서 보이는 카메라 아이콘도 카메라의 기즈모다.

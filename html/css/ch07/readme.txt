학습 목표

flexbox에 대해 알아보자
요즘은 felxbox나 Grid를 활용

flex - 유연한, 2차원 레이아웃에서 잘 작동한다.

규칙 1
flexbox는 자식을 원하는대로 움직이게 하기 위해서는 
기본적으로 부모 컨테이너(뷰, 요소)에 명시를 한다.
즉, flexbox-container 로 만들어 주면 된다.

규칙 2
주축(main axis), 교차축(cross axis)이 있다. 
justify-content, justify (현재 방향의 주축을 담당하는 속성이다.)
align-items (교차축을 담당하는 속성이다.)

기본적으로 주축을 수평이고, 교차축은 수직이다.
하지만 default이기 때문에 변결될 수 있다.

100vh (viewport Height) (스크린마다 다름)

## -threejs-09_02_Particle

https://hamhmin.github.io/threejs-09_02_Particle/

우주 particle의 버전 2.

코드 간소화 및 요소의 random color, random position 적용 그리고  AfterimagePass 효과 적용

랜덤색상, 일정 거리 이동시 카메라 위치만 초기화 되었던 것을 위치가 초기화되는 동시에 각 파티클 포인트의 위치를 랜덤으로 설정, 색상도 랜덤으로 바뀌게됨.
무한 루프 구현

Halftone, Bloom 버튼을 눌러(toggle) Effect를 추가/제거 할 수 있다.

fog를 사용하여 파티클들이 갑자기 튀어나오는듯한 느낌을 덜어 부드러운 시각 효과를 만들었다.

응용 : FirstPersonControls의 메소드 controls.movementSpeed 의 값을 sin or cos 를 2 ~ 0 ~ -2 이용하거나
속도가 빨라지고 느려지는 감각을 살려 다양한 인터렉션 기능을 추가할 수 있겠다.

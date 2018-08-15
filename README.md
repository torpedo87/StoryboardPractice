# storyboard 사용 시 팁

- 레이아웃이 원하는 대로 안나오는 경우는 크기가 정해져있지 않은 경우를 의심해보자
- size to fit : Editor 메뉴에서 클릭하거나, 단축키 command + =
- 레이아웃 포함해서 복사 : command + D, 또는 옵션키 + 드래그
- view 계층구조 파악 : shift + 마우스 오른쪽버튼
- stackView를 사용해서 subvi w들의 레이아웃을 관리하기 쉽다
- flexible 한 레이아웃을 적용하고 싶으면 autoresizing에서 설정한 것을 해제하면 된다
- stackview 사용하고 싶을 때, stackview 안에 서브 뷰들을 드래그해서 넣거나, 서브뷰들을 멀티선택해서 embed 클릭해도 됨
- update frame : constraint 수정 시 기존의 것으로 되돌리기, option + command+ =
- update constraints : 수정한 값으로 적용하기
- intrinsic size 가 없는 것은 크기를 지정해줘야 한다
- 뷰 간의 상대적 레이아웃을 지정하려면 오른쪽 버튼 드래그
- 동등한 관계에서 상대적 레이아웃을 잡으려면 둘 다 선택 후 align 설정
- hugging : 본연의 크기를 유지하려는 성질, 유지못하면 내크기보다 커진다
- compression: 본연의 크기를 유지하려는 성질, 유지못하면 작아진다
- 각 레이아웃의 우선순위 설정 가능
- vary for traits : 디바이스 방향에 따라 다른 레이아웃 설정 가능
- scrollview 의 contentsView 의 bottom 은 컨텐츠에 따라 변할수도 있으므로 priority 를 기본값보다 낮춘다
- storyboard 에서 탑마진을 0으로 잡아도 20 정도 떨어져서 나오는 이유는 status bar 때문이다
- constraint to margin : 적용하면 superview인지, 디바이스 기종에 따라 다르게 적용된다. 시스템에서 자동으로 지정해주는 마진. 자신이 원하는 마진 수치가 정해져 있다면 적용안하는게 낫다



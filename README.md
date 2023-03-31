# 구글 클론 코딩

과제 결과물 : https://likeagoogle.netlify.app/

과제 결과물의 원본 사이트 : https://www.google.com/

구글 클론 코딩입니다.

클론 사이트의 검색창에 입력하면 구글에서 검색되게 하였고, 

다크 모드도 구현해봤습니다.

앱 모음과 설정은 드롭 다운 메뉴를 통해서 구현했는데 구글 사이트와는 차이가 많이 있습니다.

드롭다운 메뉴와 다크 모드 부분은 자바스크립트로 구현했습니다.

기타 입력도구, 음성검색, 이미지 검색 및 의견 보내기 기능은 구현하지 못 했습니다.

***

# 수정

### 수정 2023/03/29/PM 12:20

다크 모드 시에 앱 모음 드롭 다운 메뉴 배경색 수정 및 css 좀 더 직관적으로 볼 수 있게 구분.

### 수정 2023/03/29/PM 12:48

하단 설정 메뉴의 드롭다운 메뉴가 나타날시 화면이 밀려 좌우 스크롤바가 생성됨. -> 스크롤바가 생성되지 않게 css조정.

### 수정 2023/03/29/PM 03:34

설정 탭에서 다크 모드 시에 라이트 모드인지, 다크 모드인지 좀 더 직관적으로 볼 수 있게, light_mode, dark_mode 이모지 추가.

앱 모음 드롭 다운 메뉴에 oveflow를 사용해서 스크롤 바 생성 및 다크 모드, 라이트 모드 일 때 이용자가 보기 편하게 -webkit-scrollbar를 사용하여 변경.

앱 모음 드롭 다운 메뉴에 이미지 추가, 이미지를 누르면 정해진 링크로 이동하게 변경.

### 수정 2023/03/29/PM 09:46

다크 모드 시에 전체 창 화면 스크롤 바가 변경됨 -> 기존 설정대로 유지 되게 수정.

### 수정 2023/03/30/PM 08:12

apps버튼과 설정버튼을 클릭했을 때 나타나는 메뉴창이 다른 화면을 클릭했을 때 사라지지 않는 점을 수정. (다른 요소를 클릭해도 메뉴창이 사라지게 수정.)

설정 메뉴창 크기 수정

### 수정 2023/03/31/PM 03:33

앱 모음 이미지 추가 및 배열 수정.

각 링크 삭제 동작하지 않게 수정. (이제 버튼을 눌러도 링크로 이동하지 않게 수정했습니다.)

구글 검색 기능은 동작, 구글 검색 버튼만 누를 경우에 구글 원본 페이지로 이동


### 수정 2023/03/31/PM 08:00

일부 css 수정

### 수정 2023/04/01/AM 02:45

화면의 크기가 작아졌을 때 검색창 내부에 div요소가 검색창 밖으로 밀려나가는 현상 수정.

모바일로 봤을 때 footer 밑에 부분이 여백으로 나오던 현상 수정.

다크모드 부분 클릭 이벤트 수정.
(이전에는 다크모드 버튼과 이모지가 따로 구분이 되어있어서 이모지 부분을 눌렀을 경우 다크모드가 실행되지 않았음. 자식 요소인 버튼에 클릭 이벤트를 주는게 아니라 부모 요소에 클릭 이벤트를 줌.)

***

# 개선하고 싶은 점

모바일로 봤을 때 레이아웃 자체는 비슷하게 나오는거 같은데 방법이 잘 못 된 느낌, 
다른 방안을 모색해 볼 것.

구글 앱 모음 메뉴창 구성 방식에 대해 더 나은 방향을 찾아 볼 것.

툴팁 표시 부분 css로 구현해 볼 것. (google앱, 입력도구, 음성검색, 이미지로 검색)

의견 보내기 부분 구현해 볼 것.


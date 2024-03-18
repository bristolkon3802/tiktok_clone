# tiktok_clone

- flutter --version

### 프로젝트 설치

- flutter create tiktok_clone
- https://nomadcoders.co/downloads/tiktok.zip

### 설치 파일 및 버전

    - Flutter 3.16.9    /   3.3.10
    - Dart 3.2.6        /   2.18.6
    - dependencies:
        font_awesome_flutter: 10.3.0     /   폰트 아이콘

### 파일 설명

- sizes
- gaps > 너비나 높이를 가지는 SizedBox

### 위젯 설명

- CupertinoDatePicker() > (iOS 스타일) 위젯 라이브러리에 속하는 날짜 및 시간 선택기
- TextEditingController() > 텍스트 필드의 현재 값을 읽거나, 텍스트 필드에 초기값을 설정하거나, 텍스트 필드의 값을 변경하는 등의 작업
- bottomNavigationBar() > 화면 하단에 고정
- SizedBox > 기본적으로 고정된 크기를 갖는 Container
- AnimatedContainer > 애니메이션을 만들 수 있음
- TextField > 입력 창을 주는 위젯
- Form > 모든 입을 한번에 검증해 줌
- TextFormFilId

### 필드 설명

    Navigator.of(context).push(MaterialPageRoute(
        builder: (context) => (),
    ));

    TextField(
        decoration: InputDecoration(
        hintText: "Username",
        enabledBorder: UnderlineInputBorder(
            borderSide: BorderSide(color: Colors.grey.shade400),
        ),
        focusedBorder: UnderlineInputBorder(
            borderSide: BorderSide(color: Colors.grey.shade400),
        ),
        ),
        cursorColor: Theme.of(context).primaryColor,
    ),

### 버튼 모음

    FractionallySizedBox(
        widthFactor: 1,
        child: Container(
        padding: const EdgeInsets.symmetric(vertical: Sizes.size16),
        decoration: BoxDecoration(
            color: Theme.of(context).primaryColor,
        ),
        child: const Text(
            "Next",
            textAlign: TextAlign.center,
            style: TextStyle(
            color: Colors.white,
            fontWeight: FontWeight.w600,
            ),
        ),
        ),
    )

### 위젯 사용 방법

    - 하단에 고정
    bottomNavigationBar: BottomAppBar(
      child: ,
    ),

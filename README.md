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

### 문법 설명

- SizedBox > 기본적으로 고정된 크기를 갖는 Container

### 필드 설명

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

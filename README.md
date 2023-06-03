# git 사용법

### 1. 계정 연결하기

* 처음에만 하면 되는 과정
```  
git config --global user.email "github 이메일주소"
git config --global user.name "github 계정"
```

### 2. 깃 저장소 만들기
* cd 명령어로 깃 저장소로 이용할 경로로 이동
* 이동한 위치에서 깃 저장소 생성하기
```
cd C:\project
git init
```
* .git 폴더 생성 확인

### 3. 원격 저장소 등록하기
![image](https://github.com/EunJi9739/boot2/assets/133085347/7656a3d2-112b-4448-9f66-737fcd134dfc)
* 위 이미지에서 복사한 SSH 값을 아래와 같이 입력
```
git remote add origin git@github.com:EunJi9739/test.git
```

### 4. 변경된 파일 업로드하기
* 변경된 모든 파일을 스테이지에 올리기
```
git add .
```

* 특정 파일만 스테이지에 올리기
```
git add 파일명/해당 파일 경로
```

### 5. 커밋하기
```
git commit -m "수정하거나 새로 작업한 내용 작성"
```

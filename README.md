# 🥇 두부두부 LOTTE PROJECT
: 롯데 직원 - 롯데 취준생 소통 창구

# ABOUT DEV 👨‍💻

## teammates 🦁

|teammate|role|
|---|---|
|`lim`(본인)|backend lead|
|`gil`|front/back-end & deploy|
|`geum`|backend & mainpage|
|`eunjin`|backend & register|
|`jongmyung`|frontend & managing|
|`umin`|frontend & design|

- 직원과 취업준비생의 소통창구를 게시판 형식으로 구성
- CRUD를 기반으로 게시판 개발 및 서비스 제공
- 롯데 84개 각 계열사마다 게시판 개설하여 취업준비생의 맞춤 계시판에 접속 가능

### 아쉬운 점
- 롯데 관련 API를 사용하지 못한점
- 84개 계열사 직접 하드코딩
- CRUD 이외의 차별화 부재

<hr/>

## 🔨 개발 규칙
### 🔒 Django
: 가상 환경 ```.gitignore```로 두고 각자 따로 사용하기
> 디폴트로 myvenv 적어뒀으니까 각자 가상 환경 이름 ```.gitignore```에 추가하기

### 🔒 DB
: ```db.sqlite3```를 ```.gitignore```로 두고 pull 받을 때 마다 명령어 입력해 업데이트하기
> DB 꼬임 방지
```
python manage.py makemigrations
python manage.py migrate
```

### 🔑 COMMIT MESSAGE
```
[본인이름] | 한 작업
ex) [종명] | 게시글 상세 페이지 수정
```

### 🔓 FE + BE
: 따로 레포를 파서 작업 후 합쳐잉

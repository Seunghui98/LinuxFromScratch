# 0.Prepare

- window 환경내에 wsl의 ubuntu 20.04 설치
- Linux mkfs 명령어
![image](https://github.com/Seunghui98/LinuxFromScratch/assets/54658745/2fb865e1-f0b9-48d1-99bd-3fc3b74f2dfa)
- Linux에서 ext3, ext4, xfs 등등 파일 시스템으로 포멧하여 사용
- 디스크를 추가하는 절차
  - 디스크 추가 -> 디스크 인식 확인 -> 파티션 생성 및 분할 여부 -> 파일 시스템 설정 -> 연결할 디렉토리 생성 -> 추가한 디스크와 생성한 디렉토리 연결
- Linux mkfs 사용법
1. mkfs 문법
```
$ mkfs -t [파일 시스템] [장치 이름]
$ mkfs.[파일 시스템] [장치 이름]
```

2. 연결 디렉토리
```
$ mkdir /disk1
```



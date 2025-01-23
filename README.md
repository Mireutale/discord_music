# 25.1.20일 이후 작동안함..(유튜브 api 관련 업데이트)
---
# Discord music bot
- 선행과정
- pip install discord.py
- pip install yt_dlp
- pip install PyNaCl
- pip install ffmpeg
- ffmpeg는 따로 오픈소스 다운로드 필요 [링크](https://ffmpeg.org/download.html)

- 디스코드 봇 생성 [링크](https://discord.com/developers/docs/intro)
- application -> New application
- installation의 링크를 통해서 추가할 서버에 등록
- Oauth2에서 bot과 administrator 체크 후 링크를 통해서 추가할 서버에 등록
- bot에서 Presence Intent/Server Members Intent/Message Content Intent 활성화 후 사용할 토큰 발급

- python코드 실행 후 디스코드 채팅으로 명령어 입력

## 사용법
- !실행 url(여러개 입력시 자동 대기열 생성)
- !중지
- !대기열

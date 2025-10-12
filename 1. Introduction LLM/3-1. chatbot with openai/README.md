---
style: |
  img {
    display: block;
    float: none;
    margin-left: auto;
    margin-right: auto;
  }
marp: true
paginate: true
---
# OpenAI를 이용한 Chatbot 예제 

- [OpenAI](https://openai.com/)
  - 오픈AI는 프렌들리 AI를 제고하고 개발함으로써 전적으로 인류에게 이익을 주는 것을 목표로 하는 미국의 인공지능 연구소이다. 
  - 이윤을 목적으로 하는 기업 OpenAI LP와 그 모체 조직인 비영리 단체 OpenAI Inc로 구성되어 있다.


---
## 가상환경
1. 챗봇 프로젝트 폴더로 이동
2. 가상환경 만들기
```shell 
uv venv .venv
```
3. 가상환경 접속
```shell 
.\.venv\Scripts\activate
```
4. 라이브러리 설치 
```shell
uv pip install -r .\requirements.txt
```

---
## 챗봇 실행 
1. `.env_sample`을 이용해서 `.env`파일 생성 
2. `.env`파일에 `OPENAI_API_KEY` 입력 
3. streamlit 실행 
```shell
streamlit run chatbot.py
```


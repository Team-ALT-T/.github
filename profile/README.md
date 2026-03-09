<h1 align="center">✈️ Truvel ✈️</h1>
<div align="center"> 
<h3><b> True travel experience tailored to you. </b></h3><br>
<img width="1503" src="https://github.com/user-attachments/assets/597a6a4b-015c-459b-a0ea-de60ba4dd3ea" alt="대표 이미지">
<h3><b>True + Travel = Truvel</b></h3>
<br>
</div>

<h3 align="center">TRUVEL은 지인과 함께하는 여행 계획을 빠르고 간편하게 만들어주는 서비스를 제공합니다.</h3>


# 📖 Table of contents
* [Introduction](#-introduction)
* [Demo](#-demo)
* [API](#-api)
* [System Architecture](#-system-architecture)
* [ERD](#-erd)
* [Tech Stack](#-tech-stack)
* [Directory Structure](#-directory-structure)
* [How to start](#-how-to-start)
* [Team Members](https://github.com/Team-ALT-T/.github/blob/main/profile/README.md#%E2%80%8D%E2%80%8D%E2%80%8D-team-members)

<br>

# 📣 Introduction
### URL
> 🗝️ [Truvel]

### Medium
> 🔎 [Truvel Medium](추후 추가 예정) &nbsp;

<br>

- **위치 맞춤 여행 추천 서비스**
- **True + Travel = Truvel (사용자에게 ‘진짜 맞는 여행’을 찾는 서비스)**
- **사용자는 추천 여행지를 저장하고 자신만의 여행 계획을 구성**
- **기록된 여행 계획과 방문 기록을 언제든지 다시 확인 가능**
- **선택한 여행지들을 지도에서 선으로 연결해 이동 경로와 거리 정보를 시각적으로 제공**
- **친구 초대 기능을 통해 함께 여행 계획을 공유하고 공동으로 일정 구성 가능**

<br>

# 🖥️ Demo
### Innit Animation
> AILIBI에 접속하면 가장 먼저 보이는 화면입니다.
<br>
<img align="center" width="1000" alt="Onboarding" src="">
<br><br>

### Login/Register
> E-mail 기반 로그인 및 회원가입으로 손쉽게 로그인 할 수 있습니다.
<br>
<img align="center" width="1000" alt="Login & Sign up" src="">
<br><br>

### Main
> 성공적인 로그인 이후 게임 플레이를 위한 메인 페이지로 이동합니다.
<br>
<img align="center" width="1000" alt="Login & Sign up" src="">
<br><br>

### Make-Scenario
> 사용자가 탐정 스토리의 주요 배경과 사건을 설정하는 페이지입니다.<br>
> 사건의 종류, 시간, 장소를 선택할 수 있습니다.
<br>
<img align="center" width="1000" alt="Login & Sign up" src="">
<br><br>

### Loading
> 사용자 입력을 기반으로 AI의 시나리오 생성을 기다리는 페이지입니다.<br>
> 평균적으로 약 1분 내외의 시간이 소요되며, 기다림을 달래 줄 2개의 미니게임(슈팅 게임, 스도쿠)이 준비되어 있습니다.
<br>
<img align="center" width="1000" alt="" src="">
<br><br>

### Initial-Statement
> 용의자들의 초기 진술을 확인할 수 있는 페이지입니다.
<br>
<img align="center" width="1000" alt="" src="">
<br><br>

### Scenario & Evidence
> 생성된 시나리오와 증거를 탐색할 수 있는 페이지 입니다.<br>
> 추리 노트를 사용하여, 사용자만의 추리 내용을 작성할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src=""><br><br>
<img align="center" width="1000" alt="" src="">
<br><br>
  
### Suspect
> 용의자 목록을 확인할 수 있는 페이지입니다.
<br>
<img align="center" width="1000" alt="" src="">
<br><br>

### Interrogation
> AI와 Websocket을 기반으로 용의자를 심문하는 페이지입니다.<br>
> STT와 TTS로 보다 몰입도 높은 플레이를 진행할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="">
<br><br>

### Choose
> 앞서 추리한 내용을 기반으로 범인을 지목하는 페이지 입니다.<br>
> 사용자의 선택에 따라 문장이 달라집니다.<br>
> 성공 — You got it right!<br>
> 실패 — Are you serious?
<br>
<img align="center" width="1000" alt="" src="">
<br><br>

### Ending-Credit
> 사건이 종료된 이후의 페이지로, 플레이 결과와 크레딧 화면을 볼 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="">
<br><br>

### History
> 사용자가 플레이 했던 내역들을 자세하게 확인할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="">
<br><br>

<br>

# 📗 API
<p align="center">
 <img width="657" height="751" alt="image" src="https://github.com/user-attachments/assets/dcd64352-cd3a-4bf2-81dd-57ece171b748" />
 <img width="650" height="810" alt="image" src="https://github.com/user-attachments/assets/eeb662c9-68ef-4e5c-9406-a26124ebf7ec" />
 <img width="645" height="182" alt="image" src="https://github.com/user-attachments/assets/0b414026-bff9-4a10-a9de-2a03196b18d1" />
</p>

# 🛠 ️System Architecture <a name="-system-architecture"></a>
<div align="center">
  <img align="center" width="1000" src="https://github.com/user-attachments/assets/d78231b8-e1dc-48e2-8974-4bdc3e80142f">
</div>
<br><br>

# 🔑 ERD
<img width="1386" height="845" alt="image" src="https://github.com/user-attachments/assets/62fb0f2d-51b7-48e8-b0fc-3c2a380af4fc" />




# 💻 Tech Stack

<div align="center">
  
 <!-- tech-stack.html -->
 <table class="tech-table">
  <tr>
    <th>분야</th>
    <th>사용 기술</th>
  </tr>
  <tr>
    <td class="field">Frontend</td>
    <td>
      <div class="badges">
        <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js">
        <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
        <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" alt="styled-components">
        <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" alt="TanStack Query">
        <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios">
      </div>
    </td>
  </tr>
  <tr>
    <td class="field">Backend</td>
    <td>
      <div class="badges">
        <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot">
        <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white" alt="Spring Security">
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
        <img src="https://img.shields.io/badge/H2_Database-003545?style=for-the-badge&logoColor=white" alt="H2">
        <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="JWT">
        <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit">
        <img src="https://img.shields.io/badge/JaCoCo-822874?style=for-the-badge&logo=jacoco&logoColor=white" alt="JaCoCo">
      </div>
    </td>
  </tr>
  <tr>
    <td class="field">DevOps</td>
    <td>
      <div class="badges">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
      </div>
    </td>
  </tr>
  <tr>
    <td class="field">etc</td>
    <td>
      <div class="badges">
        <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" alt="Swagger">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
        <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" alt="Slack">
        <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion">
      </div>
    </td>
  </tr>
</table>
<br>


<br>

# 📂 Directory Structure

<details>
  <summary>AILIBI-Backend</summary>
<pre>
<code>
🗂️AILIBI-Backend
┣ 📂.github
┃ ┣ 📂ISSUE_TEMPLATE
┃ ┗ 📂workflows
┣ 📂Backend
┃ ┣ 📃__init__.py
┃ ┣ 📃asgi.py
┃ ┣ 📃celery.py
┃ ┣ 📃settings.py
┃ ┣ 📃urls.py
┃ ┗ 📃wsgi.py
┣ 📂alertmanager
┃ ┗ 📃alertmanager.yml
┣ 📂chat
┃ ┣ 📂migrations
┃ ┣ 📂templates
┃ ┣ 📃Serializers.py
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃consumers.py
┃ ┣ 📃models.py
┃ ┣ 📃routing.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂evidence
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂grafana/data
┃ ┣ 📂alerting/1
┃ ┗ 📃grafana.db
┣ 📂health
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂llm
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂prometheus
┃ ┣ 📃alert-rules.yml
┃ ┗ 📃prometheus.yml
┣ 📂promtail
┃ ┗ 📃config.yaml
┣ 📂scenario
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃scenario_urls.py
┃ ┣ 📃serializers.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂staticfiles
┃ ┣ 📂admin
┃ ┣ 📂drf-yasg
┃ ┗ 📂rest_framework
┣ 📂stt
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂suspect
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃suspect_urls.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂tts
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃tasks.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂user
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃admin.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃tests.py
┃ ┣ 📃urls.py
┃ ┣ 📃users_urls.py
┃ ┗ 📃views.py
┣ 📃.gitattributes
┣ 📃.gitignore
┣ 📃Dockerfile
┣ 📃README.md
┣ 📃README.md
┣ 📃docker-compose-blue.yml
┣ 📃docker-compose-common.yml
┣ 📃docker-compose-green.yml
┣ 📃grafana.ini
┣ 📃manage.py
┣ 📃nginx.conf
┣ 📃requirements.txt
┗ 📃start_celery_flower.sh
</code>
</pre>
</details>
<details>
    <summary>AILIBI-Frontend</summary>
<pre>
<code>
🗂️AILIBI-Frontend
┣ 📂.github
┃ ┣ 📂ISSUE_TEMPLATE
┃ ┗ 📂workflows
┣ 📂public
┃ ┣ 📂fonts
┃ ┣ 📂images
┃ ┣ 📂mp4
┃ ┣ 📂sounds
┃ ┣ 📃logo.png
┃ ┗ 📃vite.svg
┣ 📂src
┃ ┣ 📂assets
┃ ┃ ┗ 📃react.svg
┃ ┣ 📂components
┃ ┃ ┣ 📃EndingPage.css
┃ ┃ ┣ 📃LogInPage.css
┃ ┃ ┣ 📃SignupBox.css
┃ ┃ ┗ 📃VideoPage.css
┃ ┣ 📂hooks
┃ ┃ ┣ 📃UserContext.tsx
┃ ┃ ┗ 📃axiosInstance.ts
┃ ┣ 📂mocks
┃ ┃ ┗ 📃webSocketService.ts
┃ ┣ 📂pages
┃ ┃ ┣ 📃ChattingPage.tsx
┃ ┃ ┣ 📃ChoosePage.tsx
┃ ┃ ┣ 📃EndingPage.tsx
┃ ┃ ┣ 📃EvidencePage.tsx
┃ ┃ ┣ 📃GamePage1.tsx
┃ ┃ ┣ 📃HistoryNote.tsx
┃ ┃ ┣ 📃HistoryPopUp.tsx
┃ ┃ ┣ 📃InitChatPage.tsx
┃ ┃ ┣ 📃LeftPage.tsx
┃ ┃ ┣ 📃LoadingScenarioPage.tsx
┃ ┃ ┣ 📃LogInPage.tsx
┃ ┃ ┣ 📃LoginBox.tsx
┃ ┃ ┣ 📃MainAudioContext.tsx
┃ ┃ ┣ 📃MainPage.tsx
┃ ┃ ┣ 📃MakeScenarioPage.tsx
┃ ┃ ┣ 📃NotePage.tsx
┃ ┃ ┣ 📃PlayAudioContext.tsx
┃ ┃ ┣ 📃PlayHistoryPage.tsx
┃ ┃ ┣ 📃PlayPage.tsx
┃ ┃ ┣ 📃ResultLoadingPage.tsx
┃ ┃ ┣ 📃RightPage.tsx
┃ ┃ ┣ 📃SignupBox.tsx
┃ ┃ ┣ 📃SudokuGame.tsx
┃ ┃ ┣ 📃SuspectPage.tsx
┃ ┃ ┣ 📃TTSService.tsx
┃ ┃ ┗ 📃vite-env.d.ts
┃ ┣ 📂services
┃ ┃ ┗ 📃vite-env.d.ts
┃ ┣ 📃App.css
┃ ┣ 📃App.tsx
┃ ┣ 📃index.css
┃ ┣ 📃main.tsx
┃ ┗ 📃vite-env.d.ts
┣ 📃.gitignore
┣ 📃Dockerfile
┣ 📃README.md
┣ 📃docker-compose.yml
┣ 📃eslint.config.js
┣ 📃index.html
┣ 📃package-lock.json
┣ 📃package.json
┣ 📃postcss.config.cjs
┣ 📃tailwind.config.js
┣ 📃tsconfig.app.json
┣ 📃tsconfig.json
┣ 📃tsconfig.node.json
┗ 📃vite.config.ts
</code>
</pre>
</details>
<br>

# 🧐 How To Start

### Backend 
```
git clone --recursive https://github.com/2024-Winter-Bootcamp-team-K/AILIBI-Backend.git
```
### env setting in the Backend folder
* Backend/.env
```
DB_ENGINE=
DB_NAME=
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_PORT=

OPENAI_API_KEY=

NAVER_CLIENT_ID=
NAVER_CLIENT_SECRET=

ELEVENLABS_API_KEY=
ELEVENLABS_MODEL_ID=
TASK_1_VOICE_ID=
TASK_2_VOICE_ID=
TASK_3_VOICE_ID=
```
### Run Docker
```
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml build
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml up -d
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml down

docker-compose -f docker-compose-common.yml -f docker-compose-green.yml build
docker-compose -f docker-compose-common.yml -f docker-compose-green.yml up -d
docker-compose -f docker-compose-common.yml -f docker-compose-green.yml down
```
### Frontend
```
git clone --recursive https://github.com/2024-Winter-Bootcamp-team-K/AILIBI-Frontend.git
```
### Install
```
npm run dev
```
<br>

# 👨‍👩‍👧‍👦 Team Members


<table width="1000">
    <thead>
    </thead>
    <tbody>
    <tr>
        <th>Pictures</th>
             <td width="100" align="center">
            <a href="https://github.com/AlgeMoya">
                <img width="392" height="392" alt="image" src="https://github.com/user-attachments/assets/ee3241a2-5de4-42e3-a20e-aa036a3c7251" />
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/ksm0520">
                <img width="460" height="460" alt="image" src="https://github.com/user-attachments/assets/645d8b43-2386-49bd-8568-cf92794d886d" />
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/Jimin15">
                <img width="447" height="512" alt="image" src="https://github.com/user-attachments/assets/92321095-6b74-4ef6-8d0c-6ee1a2ef4f82" />
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/chlwoomin">
                <img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/160e3ce9-17cd-4593-98b8-1ab4a2098953" />
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/penloo">
             <img width="455" height="455" alt="image" src="https://github.com/user-attachments/assets/536968f5-5f5f-406c-b53e-6d4528a77b84" />
            </a>
        </td>
        </td>
    </tr>
    <tr>
        <th>Name</th>
        <td width="100" align="center">강석규</td>
        <td width="100" align="center">김승민</td>
        <td width="100" align="center">김지민</td>
        <td width="100" align="center">최우민</td>
        <td width="100" align="center">하재민</td>
    </tr>
    <tr>
        <th>Position</th>
        <td width="150" align="center">
            Frontend<br>
            Leader<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Backend<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
        </td>
    </tr>
    <tr>
        <th>GitHub</th>
        <td width="100" align="center">
            <a href="https://github.com/AlgeMoya">
                <img src="http://img.shields.io/badge/AlgeMoya-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/ksm0520">
                <img src="http://img.shields.io/badge/ksm0520-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/Jimin15">
                <img src="http://img.shields.io/badge/Jimin15-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/chlwoomin">
                <img src="http://img.shields.io/badge/chlwoomin-green?style=social&logo=github"/>
            </a>
        </td>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/penloo">
                <img src="http://img.shields.io/badge/penloo-green?style=social&logo=github"/>
            </a>
        </td>
    </tr>
    </tbody>
</table>


























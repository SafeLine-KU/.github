<p align="center">
<img src="https://avatars.githubusercontent.com/u/157958039?s=200&v=4" width=15%><br>
Solution to increase users' disaster literacy<br>
<strong>SafeLine</strong>
</p>

# SafeLine-Server

> This `README` is written in English, with a [Korean version(한국어)](#safeline-server-한국어-해설) below.

This organisation contains the SafeLine project.  
This document contains a brief description of the project and its implementation (configuration).

## 📖 Overview

> Many people are not prepared for disasters. Current disaster warning systems and responses have limitations.

**SafeLine** is a solution aimed at improving users' disaster literacy.

- It generates instructions considering the user's location and situation (characteristics of the place, age, disabilities, etc.) and guides them to shelters.
- It creates intuitive images to accurately convey instructions even to users who find it difficult to understand text.
- It utilizes generative AI to respond to nex and complex disasters (such as climate change).
- By providing essay quizzes and feedback, it allows users to interact with the system and learn response methods.

## ⚙️ Configure and How to Run  

This project maintains `Application` and `Server` as separate repositories.  
Please refer to the two repositories below.

- [🔗 `Application` Repository](https://github.com/SafeLine-KU/SafeLine-App)
- [🔗 `Server` Repository](https://github.com/SafeLine-KU/SafeLine-Server)

## 💻 Products/Platforms Used

- `Flutter`
- `Google Maps`
- `Google Cloud Platform`
  - `Cloud Run`
  - `Cloud Storage`
  - `BigQuery`
- Generative AI
  - `Gemini`(Pro 1.0 model)
  - `DALL·E 3`
- `FastAPI`

---

# SafeLine-Server 한국어 해설

이 Organization은 SafeLine 프로젝트를 담고 있습니다.  
본 문서는 프로젝트에 대한 간단한 설명과 실행(구성)에 관한 내용을 담고 있습니다.  

## 📖 개요  

> 많은 이는 재난 속에서 원활히 대응하지 못한다. 지금의 재난 경고 시스템과 대응법에 한계가 있다.  

**SafeLine**은 사용자의 재난 문해력을 향상시키기 위한 솔루션입니다.  

- 사용자의 위치와 상황(장소의 특성, 나이, 장애 등)을 고려해 행동요령을 생성하고, 대피소와 함께 안내합니다.
- 직관적인 이미지를 생성하여, 글을 이해하기 어려운 사용자에게도 정확하게 행동요령을 전달합니다.  
- 생성형 AI를 활용해, 신종,복합재난(기후변화 등)까지 대응합니다.
- 주관식 방식의 퀴즈와 피드백을 제공함으로써 사용자가 시스템과 상호작용하며, 대응법을 익힐 수 있도록 합니다.

## ⚙ 구성 및 실행방법

본 프로젝트는 `Application`과 `Server`를 별도의 레포지토리로 관리중입니다.  
아래 두개의 레포지토리를 참고하여 실행해주세요.  

- [🔗 `Application` Repository](https://github.com/SafeLine-KU/SafeLine-App)
- [🔗 `Server` Repository](https://github.com/SafeLine-KU/SafeLine-Server)

## 💻 사용한 제품/플랫폼  

- `Flutter`
- `Google Maps`
- `Google Cloud Platform`
  - `Cloud Run`
  - `Cloud Storage`
  - `BigQuery`
- Generative AI
  - `Gemini`(Pro 1.0 model)
  - `DALL·E 3`
- `FastAPI`

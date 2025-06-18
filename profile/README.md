
# Fitmate

**맞춤 운동 루틴 추천 웹 애플리케이션**

Fitmate는 사용자의 체력 수준과 운동 목적에 맞는 **개인 맞춤형 운동 루틴**을 추천해주는 웹 서비스입니다. 운동 정보 제공, 루틴 저장 및 기록 기능을 포함하여 헬스 입문자들도 손쉽게 운동을 시작하고 지속할 수 있도록 돕습니다.

## 💡 프로젝트 배경

![image](https://github.com/user-attachments/assets/4e5f558f-8a73-4801-8e35-94c5377bd194)


국민체력실태조사 및 사용자 인터뷰 등을 통해 다음과 같은 문제점을 발견하였습니다:

- 자신에게 맞는 운동 루틴을 찾기 어렵다
- 운동 루틴을 직접 구성하는 것이 어렵다
- 운동 정보가 여러 곳에 분산되어 있다

이러한 문제를 해결하기 위해, **Fitmate는 AI 및 외부 운동 API를 활용한 자동 루틴 생성 및 운동 정보 제공** 기능을 제공합니다.

## 🎯 주요 기능


![image](https://github.com/user-attachments/assets/1196942f-3e2a-4eb0-9267-528b60b4db06)


- **맞춤형 운동 루틴 추천**:  
  사용자의 신체 정보 및 운동 목적을 기반으로 OpenAI의 ChatGPT API를 활용하여 개인 맞춤 루틴 생성

- **운동 정보 제공**:  
  Wger Exercise API를 활용하여 운동 이름, 설명, 필요한 장비, 이미지 등의 정보를 제공

- **루틴 저장 및 기록**:  
  생성된 루틴을 저장하고 기록할 수 있는 기능 제공

## 🛠 기술 스택

### 🔹 Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

### 🔹 Backend

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

### 🔹 API & 외부 서비스

![ChatGPT API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Wger Exercise API](https://img.shields.io/badge/Wger_API-000000?style=for-the-badge)
![Google Cloud Translation API](https://img.shields.io/badge/Google_Cloud_Translation-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)


## 🖥 시스템 아키텍처


![image](https://github.com/user-attachments/assets/3f9ec81b-1b11-489a-82f2-2fabe4587afb)


- 프론트엔드는 React/Vite 기반 SPA
- 백엔드는 Spring Boot 기반 REST API 서버
- MongoDB를 활용한 NoSQL 데이터 저장
- AWS EC2를 이용한 서버 배포

## 🎬 시연 영상

👉 [영상 바로 보기](https://youtu.be/W-9T7BsV9C0)


## 🙋 팀원 소개 (어쩌다모인팀)

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/ghdals">
          <img src="https://avatars.githubusercontent.com/ghdals" width="100px;" alt="신홍민"/>
          <br /><sub><b>FE 팀장<br/>신홍민</b></sub>
        </a><br />
      </td>
      <td align="center">
        <a href="https://github.com/takhhan">
          <img src="https://avatars.githubusercontent.com/takhhan" width="100px;" alt="한승제"/>
          <br /><sub><b>FE 팀원<br/>한승제</b></sub>
        </a><br />
      </td>
      <td align="center">
        <a href="https://github.com/cjs-0513">
          <img src="https://avatars.githubusercontent.com/cjs-0513" width="100px;" alt="최준성"/>
          <br /><sub><b>BE 팀원<br/>최준성</b></sub>
        </a><br />
      </td>
      <td align="center">
        <a href="https://github.com/prijh0721">
          <img src="https://avatars.githubusercontent.com/prijh0721" width="100px;" alt="유승환"/>
          <br /><sub><b>BE 팀원<br/>유승환</b></sub>
        </a><br />
      </td>
      <td align="center">
        <a href="https://github.com/yshskek">
          <img src="https://avatars.githubusercontent.com/yshskek" width="100px;" alt="이재환"/>
          <br /><sub><b>BE 팀원<br/>이재환</b></sub>
        </a><br />
      </td>
    </tr>
  </tbody>
</table>


## 📌 향후 개선 방향

- 모바일 애플리케이션 확장
- UI/UX 디자인 개선
- 사용자 피드백 기반 기능 개선
- 동기부여 요소 (뱃지, 알림 등) 추가

## 📊 자료 모음

- [fitmate_발표자료.pptx](https://github.com/user-attachments/files/20750128/fitmate_.pptx)

---

> **Fitmate는 헬스 입문자들도 쉽게 운동 루틴을 시작하고 지속할 수 있도록 돕는 맞춤형 운동 파트너입니다.**

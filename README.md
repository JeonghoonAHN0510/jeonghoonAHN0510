<div align="center">

<!-- header: 높이 축소 & 색상 통일 -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=header&fontColor=FFFFFF&theme=cobalt" alt="header"/>

<h3>"꾸준함으로 부족한 점을 극복해나가는 개발자, <b>안정훈</b> 입니다."</h3>

</div>

---

## 🛠️ Tech Stacks
<div align="center">

<!-- 배지 크기와 여백 통일: for-the-badge 유지, 행·열 정리 -->
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white" />
<img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=black" />
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=0A0A0A" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" />
<img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />

</div>

---

## 💡 LC-Eye 프로젝트
> **기간:** 2025.11.05 ~ 2025.11.27 (3주)  
> **기술스택:** Spring Boot · React · Flutter  
> **역할:** 버전 관리 / 보안 아키텍쳐 설계 / 서버 부하 분산

**LC-Eye**는 실무 LCI(Life Cycle Inventory) 계산과 표준 데이터 자동 매핑 기능을 제공하는 **경량형 LCI 시스템**입니다. <br />
복잡한 LCI 계산 과정을 자동화하고 데이터 관리의 효율성을 높이는 것을 목표로 했습니다.

**핵심 구현**
- **LCI 계산 알고리즘** : 단위 변환 로직을 포함한 제품 단위 LCI 계산 알고리즘 구현
- **자동 매핑 시스템** : 표준 Flow 데이터와 텍스트 유사도(Text Similarity)를 활용하여 LCI 데이터 자동 매핑 시스템 구축
- **데이터 격리 및 보안** : 멀티테넌시를 고려하여 기업별 데이터 독립성 확보 및 역할 기반 접근 제어 구현

**성과**
- **서버 안정성 확보** : 기능별 서버 분리 아키텍쳐 설계를 통한 서버 과부하 방지
- **데이터 보안 강화** : 회원 권한별 접근 인가 설정을 통한 내부 데이터 보안 수준 향상

> 🔗 [Notion 바로가기](https://www.notion.so/lceye/LC-Eye-2a2094d4983480369aa4fe1a6163688f?source=copy_link)  
---

# 🗺️ K-Tour 프로젝트
> **기간:** 2025.09.26 ~ 2025.10.31 (4주)  
> **기술스택:** Spring Boot · React · MyBatis · Firebase  
> **역할:** 멀티테넌시 아키텍쳐 설계 / 동적 서브도메인 라우팅 / DB 정규화 및 마이그레이션 / 지도 API 총괄

**K-Tour**는 구독자(기업)별 맞춤형 관광 정보를 제공하는 **SaaS 기반 지도 서비스**입니다. <br />
공공데이터(TourAPI)를 정규화하여, 구독자에게 **개별 서브도메인**과 **독립된 DB**를 제공하는 멀티테넌시 아키텍쳐를 구축했습니다.

**핵심 구현**
- **데이터 정규화** : 공공데이터를 분석하여 동적 테이블을 생성하고, 관광지 정보를 일관된 기준으로 정규화하는 마이그레이션 로직 구현
- **멀티테넌시 아키텍쳐** : SaaS 모델을 기반으로, 구독자별로 DB를 분리하여 데이터 격리성 확보
- **동적 라우팅** : 사용자가 요청한 **서브도메인**을 식별하여, 해당 구독자의 고유 DB에 자동으로 연결하는 **동적 라우팅** 구현

**성과**
- **구독자별 데이터 격리** : 멀티테넌시 아키텍쳐 설계를 통해 **높은 수준의 보안성**과 **데이터 프라이버시** 확보
- **서비스 확장성 및 안정성 확보** : 서브도메인 기반의 DB 접근 분리 설계를 통해 **서비스 안정성** 확보

> 🔗 [GitHub 바로가기](https://github.com/JeonghoonAHN0510/K-Tour_Refactor)  
> 🔗 [발표자료 보기](https://buly.kr/BeLJkTI)

---

## 🥩 BestMeat 프로젝트
> **기간:** 2025.08.22 ~ 2025.09.12 (3주)  
> **기술스택:** Spring Boot · JSP · WebSocket  
> **역할:** **팀 리더(조장)** / 실시간 채팅 구현 / 서버 부하 분산

**BestMeat**는 사용자가 여러 정육점의 가격과 정보를 <br/>
**실시간 채팅**으로 비교하고 문의할 수 있는 비대면 중개 플랫폼입니다.

**핵심 구현**
- **실시간 채팅(WebSocket)** : WebSocket을 활용하여 실시간 양방향 통신 기능 구현
- **서버 과부하 감소** : 대량의 채팅 로그를 CSV로 임시 저장하여 DB 저장 부하 방지
- **비동기 처리** : 문자 발송, 결제 API 호출 등 외부 API 연동 작업을 비동기 처리로 변경하여 시스템 리소스 효율화

**성과**
- **평균 응답 시간 90% 단축** : 외부 API의 비동기 처리를 통해 **사용자 경험 극대화**
- **서버 안정성 확보** : CSV 로그 관리 및 배치 처리 도입을 통한 **안정적인 DB 성능** 유지
- **팀 리더 역할 수행** : 팀장으로서 일정 관리, 팀원 간 업무 조정을 주도하여 프로젝트를 **성공적으로 완수**

> 🔗 [GitHub 바로가기](https://github.com/jihoons1/2025_PJ3_4team_project)  
> 🔗 [발표자료 보기](https://buly.kr/8Trg5mI)

---

## 🏅 GitHub Stats
<!-- 2열 그리드: 표 대신 테이블을 사용해 자연스러운 사이즈 제어 -->
<table align="center">
  <tr>
    <td align="center">
      <!-- Streak: radius/테두리 통일 -->
      <img src="https://streak-stats.demolab.com?user=jeonghoonAHN0510&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3" alt="streak"/>
    </td>
    <td align="center">
      <!-- 종합 통계: 아이콘 표시, 테마 통일 -->
      <img src="https://github-readme-stats.vercel.app/api?username=JeonghoonAHN0510&show_icons=true&theme=radical" alt="stats"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <!-- Top Langs: compact, width 살짝 축소 -->
      <img src="https://github-readme-stats.vercel.app/api/top-langs?username=jeonghoonAHN0510&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" alt="top langs"/>
    </td>
  </tr>
</table>

---

## 🌱 Solved.ac
<div align="center">

<!-- 뱃지 높이 균형: width 지정으로 과도한 폭 방지 -->
<a href="https://solved.ac/JeonghoonAHN0510">
  <img src="http://mazassumnida.wtf/api/generate_badge?boj=JeonghoonAHN0510" alt="solved.ac badge" height="150"/>
</a>
<img src="http://mazandi.herokuapp.com/api?handle=JeonghoonAHN0510&theme=warm" alt="mazandi profile" height="150"/>

</div>

---

## 🧑‍💻 Contact
<div align="center">

<a href="https://velog.io/@jeonghoonahn/posts">
  <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=Velog&logoColor=white" />
</a>
<a href="https://github.com/JeonghoonAHN0510">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white" />
</a>
<a href="mailto:jeonghoonahn0510@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white" />
</a>

</div>

---

<div align="center">

<!-- footer: 높이 축소 & 색상 통일 -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&fontColor=FFFFFF&theme=cobalt" alt="footer"/>

</div>

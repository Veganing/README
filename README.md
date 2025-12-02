# 🌱 VeGaning

<div align="center">
  
<img width="432" height="200" alt="스크린샷 2025-12-01 오후 5 31 27" src="https://github.com/user-attachments/assets/1f428af4-325b-42bd-8b61-b8e3574b622a" />


**30일 비건 챌린지로 건강한 식습관과 환경 보호를 실천하세요**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/your-repo/veganing)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)](https://react.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## 📑 목차
- [프로젝트 소개](#-프로젝트-소개)
- [주요 기능](#-주요-기능)
- [기술 스택](#-기술-스택)
- [시스템 아키텍처](#-시스템-아키텍처)
- [팀원 소개](#-팀원-소개)
- [개발 환경](#%EF%B8%8F-개발-환경-및-ide)
- [시작하기](#-시작하기)
- [주요 구현 사항](#-주요-구현-사항)
- [트러블슈팅](#-트러블슈팅)

---

## 💡 프로젝트 소개

**VeGaning**은 MZ 세대를 중심으로 확산 중인 비건 트렌드와 환경 인식을 결합한 30일 비건 챌린지 플랫폼입니다.

### 개발 배경
- MZ 세대를 중심으로 확산 중인 비건 트렌드와 환경 인식 증가
- 실천을 지속하기 어려운 문제 존재
- "챌린지 + AI 분석 + 시각화"를 결합한 플랫폼 제안

### 진행 기간
**2024.09.01 ~ 2024.11.30** (8주)

---

## ✨ 주요 기능

### 1. 30일 비건 챌린지 시작하기 📋
- 비건 타입 선택 (플렉시테리언, 페스코, 락토-오보, 비건)
- 챌린지 기간 설정 (15일/1개월/자유)
- 목표 선택 (건강 증진, 환경 보호, 동물 보호, 제중 관리)
- 선택된 타입의 비건 챌린지 시작

### 2. 식단 분석 및 영양 관리 🍽️
- AI 기반 식단 칼로리 및 영양 분석
- 오늘 먹은 식사 사진 첨부 및 분석
- 비건 적합도 평가 (비건 여부 체크)
- 영양성분 상세 정보 제공 (칼로리, 단백질, 탄수화물, 지방 등)

### 3. 탄소 발자국 시각화 📊
- 식단 기반 탄소 배출량 자동 계산
- React Recharts를 활용한 그래프 시각화
- 성취감 제공을 통한 지속적인 참여 유도
- 일/주/월 단위 탄소 절감량 통계

### 4. AI 레시피 추천 및 쇼핑 연동 🛒
- 오늘 먹은 식단을 기준으로 맞춤 레시피 추천
- 커뮤니티 인기 레시피 DB 활용한 LLM 학습
- 추천 레시피의 식재료 자동 추출
- 쇼핑탭에 필요한 식재료 자동 표시
- 클릭 한 번으로 쇼핑몰 구매 페이지 이동

### 5. 비건 커뮤니티 👥
- 다이어리 형태 식단 인증 게시판
- 지역별 순위 시스템
- 좋아요, 댓글, 공유 기능
- 인기 레시피 자동 큐레이션 페이지
- 사용자 레시피가 AI 추천 시스템에 학습됨

### 6. 비건 쇼핑몰 🏪
- 네이버 쇼핑 API를 통한 비건 제품 추천
- 무료 배송, 품질 보장, 포인트 적립 혜택
- 레시피 연동 식재료 바로 구매

### 7. 식당 위치 서비스 📍
- 네이버 지도 API를 활용한 주변 비건 식당 검색
- 식당 정보 제공 (거리, 메뉴, 리뷰 등)
- 카페, 위치정보 제공

---

## 🛠 기술 스택

### Frontend Core
<img src="https://img.shields.io/badge/React-19.1.1-61DAFB?style=flat-square&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/Vite-7.1.7-646CFF?style=flat-square&logo=vite&logoColor=white"/> <img src="https://img.shields.io/badge/React_Router-7.9.5-CA4245?style=flat-square&logo=reactrouter&logoColor=white"/>

### Styling & UI Components
<img src="https://img.shields.io/badge/Tailwind_CSS-3.4.18-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/Radix_UI-Latest-161618?style=flat-square"/> <img src="https://img.shields.io/badge/Lucide_React-0.544.0-F56565?style=flat-square&logoColor=white"/> <img src="https://img.shields.io/badge/Framer_Motion-12.23.24-0055FF?style=flat-square&logo=framer&logoColor=white"/>

**UI 라이브러리 상세**
- **Radix UI**: Avatar, Label, Progress, Slot, Tabs - 접근성 높은 헤드리스 컴포넌트
- **Tailwind CSS**: 유틸리티 우선 CSS 프레임워크
- **Framer Motion**: 애니메이션 및 인터랙션 라이브러리
- **Lucide React**: 아이콘 라이브러리

### Data Visualization
<img src="https://img.shields.io/badge/Recharts-3.5.1-8884d8?style=flat-square"/>

### Utilities
<img src="https://img.shields.io/badge/clsx-2.1.1-blue?style=flat-square"/> <img src="https://img.shields.io/badge/tailwind--merge-3.3.1-06B6D4?style=flat-square"/> <img src="https://img.shields.io/badge/CVA-0.7.1-purple?style=flat-square"/>

**유틸리티 상세**
- **clsx**: 조건부 클래스 네임 관리
- **tailwind-merge**: Tailwind 클래스 중복 제거 및 병합
- **class-variance-authority (CVA)**: 컴포넌트 variant 관리

### Backend & API
<img src="https://img.shields.io/badge/Node.js-20.19.0+-339933?style=flat-square&logo=node.js&logoColor=white"/> <img src="https://img.shields.io/badge/Express-4.x-000000?style=flat-square&logo=express&logoColor=white"/> <img src="https://img.shields.io/badge/Mock_JSON-API-FFA500?style=flat-square"/>

### External APIs
<img src="https://img.shields.io/badge/Naver_Shopping_API-03C75A?style=flat-square&logo=naver&logoColor=white"/> <img src="https://img.shields.io/badge/Naver_Map_API-03C75A?style=flat-square&logo=naver&logoColor=white"/> <img src="https://img.shields.io/badge/LLM_API-AI_Analysis-FF6F00?style=flat-square"/>

### Development Tools
<img src="https://img.shields.io/badge/ESLint-9.36.0-4B32C3?style=flat-square&logo=eslint&logoColor=white"/> <img src="https://img.shields.io/badge/PostCSS-8.5.6-DD3A0A?style=flat-square&logo=postcss&logoColor=white"/> <img src="https://img.shields.io/badge/Autoprefixer-10.4.21-DD3735?style=flat-square"/> <img src="https://img.shields.io/badge/Nodemon-3.1.10-76D04B?style=flat-square&logo=nodemon&logoColor=white"/>

### Cooperation & Communication
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white"/>

---

## 🏗 시스템 아키텍처

### 데이터 플로우

```
식단 입력 → LLM 분석 → 영양소/비건 적합도 평가
    ↓
전체 저장 → 탄소 발자국 계산 → Recharts 시각화
    ↓
레시피 추천 ← 커뮤니티 인기 DB 활용
    ↓
식재료 추출 → 쇼핑탭 자동 표시 → 구매 연동
    ↓
커뮤니티 피드 → 좋아요 수집 → 인기 레시피 DB → LLM 학습
```

---

## 👥 팀원 소개

| 이름 | 학번 | 역할 | 담당 업무 |
|------|------|------|-----------|
| 임창수 | 2131139 | Frontend | 커뮤니티, 댓글/좋아요, 광고게시판 구현, 페이지 구성 |
| 황필호 | 2271483 | Frontend/Backend | 챌린지/쇼핑몰/식당지도, 비건 식품 목록, 지도 기반 식당 검색 구현 |
| 정수연 | 2271512 | Frontend/Design | 로그인/회원가입, 웹페이지 디자인, 전체 페이지 디자인 |
| 백상준 | 2271525 | Frontend | 메인 홈페이지, 비건 쇼핑 색션, 페이지 이동 구조 설계 |

---

## ⚙️ 개발 환경 및 IDE

### Frontend
- **Language** : JavaScript (ES6+)
- **Framework** : React 19
- **Build Tool** : Vite 4.5
- **IDE** : VS Code

### Backend
- **Runtime** : Node.js 18+
- **Framework** : Express 4.18
- **IDE** : VS Code

### Design
- **Tool** : Figma
- **Style** : Tailwind CSS

---

## 🚀 시작하기

### 📋 사전 요구사항
- Node.js 18+
- npm 또는 yarn
- Git

### 1️⃣ 레포지토리 클론

```bash
# 레포지토리 클론
git clone https://github.com/your-username/veganing.git
cd veganing
```

### 2️⃣ 의존성 설치

```bash
# 프론트엔드 의존성 설치
cd frontend
npm install

# 백엔드 의존성 설치
cd ../backend
npm install
```

### 3️⃣ 환경 변수 설정

```bash
# backend/.env 파일 생성
cp .env.example .env

# .env 파일 편집 (API 키 등 설정)
NAVER_CLIENT_ID=your_naver_client_id
NAVER_CLIENT_SECRET=your_naver_client_secret
LLM_API_KEY=your_llm_api_key
PORT=3000
```

### 4️⃣ 개발 서버 실행

```bash
# 백엔드 서버 실행 (터미널 1)
cd backend
npm run dev

# 프론트엔드 개발 서버 실행 (터미널 2)
cd frontend
npm run dev
```

프론트엔드가 `http://localhost:5173`에서 실행됩니다.  
백엔드 API가 `http://localhost:3000`에서 실행됩니다.

### 5️⃣ 빌드 및 배포

```bash
# 프론트엔드 빌드
cd frontend
npm run build

# 빌드된 파일은 frontend/dist 폴더에 생성됩니다
```

---

## 🔧 주요 구현 사항

### 1. React 기반 SPA 구조

```javascript
// React Router를 활용한 페이지 라우팅
import { BrowserRouter, Routes, Route } from 'react-router-dom';

function App() {
  return (
    <BrowserRouter>
      <Routes>
        <Route path="/" element={<MainPage />} />
        <Route path="/challenge" element={<ChallengePage />} />
        <Route path="/community" element={<CommunityPage />} />
        <Route path="/shop" element={<ShopPage />} />
        <Route path="/map" element={<MapPage />} />
      </Routes>
    </BrowserRouter>
  );
}
```

### 2. LLM 기반 식단 분석

```javascript
// AI 분석 API 호출
const analyzeMeal = async (mealImage, mealDescription) => {
  try {
    const response = await axios.post('/api/analyze', {
      image: mealImage,
      description: mealDescription
    });
    
    const { nutrition, isVegan, carbonFootprint } = response.data;
    
    return {
      calories: nutrition.calories,
      protein: nutrition.protein,
      carbs: nutrition.carbs,
      fat: nutrition.fat,
      isVegan: isVegan,
      carbon: carbonFootprint
    };
  } catch (error) {
    console.error('식단 분석 실패:', error);
  }
};
```

### 3. 탄소 발자국 시각화

```javascript
import { LineChart, Line, XAxis, YAxis, CartesianGrid, Tooltip } from 'recharts';

const CarbonChart = ({ data }) => {
  return (
    <LineChart width={600} height={300} data={data}>
      <CartesianGrid strokeDasharray="3 3" />
      <XAxis dataKey="date" />
      <YAxis />
      <Tooltip />
      <Line 
        type="monotone" 
        dataKey="carbon" 
        stroke="#2D5016" 
        strokeWidth={2}
      />
    </LineChart>
  );
};
```

### 4. 레시피 추천 및 쇼핑 연동

```javascript
// 레시피 추천 시스템
const getRecommendedRecipes = async (todayMeals, popularRecipes) => {
  const response = await axios.post('/api/recommend', {
    meals: todayMeals,
    popularDb: popularRecipes
  });
  
  const recipes = response.data.recipes;
  
  // 레시피의 식재료 추출 및 쇼핑탭 연동
  const ingredients = recipes.flatMap(recipe => recipe.ingredients);
  
  return {
    recipes,
    shoppingList: ingredients
  };
};

// 쇼핑몰 연동
const navigateToShop = (ingredient) => {
  // 네이버 쇼핑 API 호출
  window.location.href = `/shop?search=${ingredient}`;
};
```

### 5. 커뮤니티 피드 및 인기 레시피 시스템

```javascript
// 좋아요 기반 인기 레시피 자동 큐레이션
const updatePopularRecipes = async () => {
  const feeds = await fetchCommunityFeeds();
  
  // 좋아요 순으로 정렬
  const popularFeeds = feeds
    .sort((a, b) => b.likes - a.likes)
    .slice(0, 10);
  
  // DB에 저장
  await saveToPopularRecipesDB(popularFeeds);
  
  // LLM 학습 데이터로 활용
  await updateLLMTrainingData(popularFeeds);
};
```

### 6. Tailwind CSS 기반 반응형 디자인

```jsx
// 모바일 우선 반응형 레이아웃
<div className="container mx-auto px-4">
  <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
    {recipes.map(recipe => (
      <div className="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition">
        <img src={recipe.image} className="w-full h-48 object-cover rounded-md" />
        <h3 className="text-xl font-bold mt-4">{recipe.title}</h3>
        <p className="text-gray-600 mt-2">{recipe.description}</p>
      </div>
    ))}
  </div>
</div>
```

---

## 🐛 트러블슈팅

### 1. LLM API 응답 지연 문제
**문제**: 식단 분석 시 LLM API 호출이 5초 이상 걸려 사용자 경험 저하

**원인**: 이미지 업로드 및 분석 처리에 시간이 오래 걸림

**해결**:
- 로딩 인디케이터 추가로 사용자 피드백 제공
- 이미지 압축 전처리로 업로드 시간 단축
- API 응답 캐싱으로 중복 요청 방지

```javascript
// 이미지 압축 처리
const compressImage = async (file) => {
  return new Promise((resolve) => {
    const reader = new FileReader();
    reader.onload = (e) => {
      const img = new Image();
      img.onload = () => {
        const canvas = document.createElement('canvas');
        const ctx = canvas.getContext('2d');
        
        // 최대 크기 제한
        const maxWidth = 800;
        const scale = maxWidth / img.width;
        
        canvas.width = maxWidth;
        canvas.height = img.height * scale;
        
        ctx.drawImage(img, 0, 0, canvas.width, canvas.height);
        canvas.toBlob(resolve, 'image/jpeg', 0.8);
      };
      img.src = e.target.result;
    };
    reader.readAsDataURL(file);
  });
};
```

### 2. 커뮤니티 피드 무한 스크롤 성능 이슈
**문제**: 피드가 많아질수록 스크롤이 버벅거리는 현상 발생

**해결**:
- React의 가상 스크롤 라이브러리 적용
- 이미지 Lazy Loading 구현
- 페이지네이션으로 한 번에 20개씩만 로드

```javascript
import { useInfiniteQuery } from 'react-query';
import { useInView } from 'react-intersection-observer';

const CommunityFeed = () => {
  const { ref, inView } = useInView();
  
  const {
    data,
    fetchNextPage,
    hasNextPage
  } = useInfiniteQuery('feeds', fetchFeeds, {
    getNextPageParam: (lastPage) => lastPage.nextCursor
  });
  
  useEffect(() => {
    if (inView && hasNextPage) {
      fetchNextPage();
    }
  }, [inView]);
  
  return (
    <div>
      {data.pages.map(page => 
        page.feeds.map(feed => <FeedCard key={feed.id} feed={feed} />)
      )}
      <div ref={ref}>Loading...</div>
    </div>
  );
};
```

### 3. 네이버 지도 API CORS 에러
**문제**: 프론트엔드에서 네이버 지도 API 직접 호출 시 CORS 에러 발생

**해결**:
- 백엔드 프록시 서버를 통한 API 호출
- Express CORS 설정 추가

```javascript
// backend/server.js
const express = require('express');
const cors = require('cors');
const axios = require('axios');

const app = express();

app.use(cors({
  origin: 'http://localhost:5173',
  credentials: true
}));

// 네이버 API 프록시
app.get('/api/map/search', async (req, res) => {
  try {
    const { query } = req.query;
    const response = await axios.get(
      `https://openapi.naver.com/v1/search/local.json`,
      {
        params: { query: `${query} 비건` },
        headers: {
          'X-Naver-Client-Id': process.env.NAVER_CLIENT_ID,
          'X-Naver-Client-Secret': process.env.NAVER_CLIENT_SECRET
        }
      }
    );
    res.json(response.data);
  } catch (error) {
    res.status(500).json({ error: error.message });
  }
});
```

### 4. Mock JSON 데이터 관리의 한계
**문제**: 개발 초기 Mock 데이터 사용으로 실제 DB 연동 시 구조 변경 필요

**해결**:
- Mock 데이터 구조를 실제 API 스펙과 동일하게 설계
- 추후 MongoDB/PostgreSQL 연동 준비

```javascript
// mock/recipes.json 구조 설계
{
  "recipes": [
    {
      "id": "recipe_001",
      "title": "두부 샐러드",
      "description": "신선한 채소와 두부로 만든 건강한 샐러드",
      "ingredients": [
        { "name": "두부", "amount": "200g" },
        { "name": "양상추", "amount": "100g" }
      ],
      "nutrition": {
        "calories": 250,
        "protein": 15,
        "carbs": 20,
        "fat": 10
      },
      "isVegan": true,
      "likes": 1247,
      "author": "비건러버",
      "createdAt": "2024-11-15"
    }
  ]
}
```

---

## 📊 기대 효과

### 사회적 효과
- 비건 실천의 지속성을 높이고 환경 보호, 동물복지에 기여

### 기술적 효과
- LLM 기반의 식단 분석 기술과 데이터 시각화의 융합 사례 제시

### 경제적 효과
- 비건 관련 제품, 식당 노출로 지역 경제 및 관련 산업 활성화

### 교육적 효과
- 데이터 기반의 지속 가능한 소비문화 확산 및 건강한 식습관 형성

---

## 📷 스크린샷

### 메인 화면
![메인화면](https://via.placeholder.com/800x450/2D5016/FFFFFF?text=Main+Page)

### 챌린지 페이지
![챌린지](https://via.placeholder.com/800x450/4CAF50/FFFFFF?text=Challenge+Page)

### 탄소 발자국 그래프
![그래프](https://via.placeholder.com/800x450/8BC34A/FFFFFF?text=Carbon+Footprint+Chart)

### 커뮤니티
![커뮤니티](https://via.placeholder.com/800x450/689F38/FFFFFF?text=Community+Feed)

---

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참고하세요.

---

## 🙏 감사의 말

이 프로젝트는 한성대학교 컴퓨터공학부 웹 프레임워크1 강의의 팀 프로젝트로 진행되었습니다.

**2팀 유비쿼장비초신**을 응원해주신 모든 분들께 감사드립니다.

---

## 📧 문의

프로젝트에 대한 문의사항이나 제안이 있으시면 아래로 연락 주세요.

- **Email**: team2@veganing.com
- **GitHub Issues**: [Issues 페이지](https://github.com/your-repo/veganing/issues)

---

<div align="center">

**⭐ Star를 눌러주시면 프로젝트 개발에 큰 힘이 됩니다!**

Made with 💚 by Team 2 (유비쿼장비초신)

</div>

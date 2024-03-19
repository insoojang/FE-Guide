# FE-Guide
2024년에 리액트 프로젝트를 시작하는 방법


### 프로젝트 시작
CRA: Vite, Webpack  
SSR: Remix, Next.js(14버전에 자체버그가 많음)  
콘텐츠 중심 정적사이트: Astro

### 패키지 매니저
기본: npm, yarn  
속도중요: npm  
모노레포: Turborepo

### 상태관리
내장: useContext, useReducer  
기존: Redux Toolkit, Redux  < 세팅 복잡함
그외: Recoil, Jotai, MobX  
추천: Zustand  < 사용이 간단하여 대세로 자리잡음

### 데이터 패칭
기본: React-query(TanStack Query)  
GraphQL: Apollo Client, urql, Relay
Redux: RTK Query  
그외: tRPC(FE/BE 둘다 Typescript일떄)   

### 라우팅
기본: React Router  
타입스크립트 지원: TanStack Router

### CSS 스타일링
CSS-in-CSS: CSS, Sass, CSS Modules, or CSS Modules with Sass    
CSS-in-JS:  Styled Components, Emotion  <서버사이드 사용X  
Utility-First-CSS: Tailwind CSS  
Zero-runtime CSS in JS: Vanilla Extract

### UI 라이브러리
Material UI(MUI): 프리랜서 프로젝트에서 가장 인기  
shadcn/ui: 2023년에 가장 있기 (주로 Tailwind와 함께사용)  
Mantine UI: 2022년에 가장 인기  
Chakra UI: 2021년에 가장 인기  
NextUI: React Aria 기반  
Park UI: Ark UI 기반  
Radix  
React Aria  
Catalyst  
Daisy UI  
Headless UI : 24년에 트렌드 (필수 컴포넌트만 존재하며 스타일링은 개발자기 직접)  
Tailwind UI (무료가 아님)  
Ark UI (Chakra UI의 제작자가 개발함)  
Ant Design: 알리바바그룹 디자인 시스템
Semantic UI  
React Bootstrap  
Reactstrap  

### 리액트 애니메이션 라이브러리
기본: Framer Motion < 가장 추천  
그외: react-spring, react-motion, react-move  

### 리액트 시각화 & 차트 라이브러리
기본: Recharts, Echart  
고수준: visx(학습곡선 높음)  
간편: Victory, nivo, react-chartjs < 커스텀마이징 어려움  

### 리액트 시각화 & 차트 라이브러리
기본: React-Hook-Form(주로 유효성검사 zod와 함께사용)

### 폴더 구조
기본:컨테이너 컴포넌트 구조(container-presenter)  
그외:아토믹, FSD  

### 인증
Lucia  
Supabase Auth  
Clerk <개인에러 추적쉬움  
AuthKit  
NextAuth  
Firebase Auth  
Auth0  
AWS Cognito  

### 국제화
기본: react-i18next  
그외: FormatJS, ingui


### 결제
기본: PayPal, Stripe (React Stripe Element  Stripe Checkout)
한국: 토스페이먼츠

### 파일업로드
기본: react-dropzone

### 메일
기본: react-email  
그외: Mailing, mjml

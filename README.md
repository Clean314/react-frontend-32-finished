# Places Share Application

이 프로젝트는 React를 사용하여 구현된 장소 공유 웹 애플리케이션입니다. 사용자들이 자신이 방문한 장소를 공유하고 다른 사용자들의 장소를 볼 수 있는 플랫폼을 제공합니다.

## 주요 기능

- 사용자 인증 (로그인/회원가입)
- 장소 등록 및 수정
- 장소 목록 조회
- 사용자별 장소 관리
- 지도를 통한 장소 시각화
- 반응형 디자인

## 기술 스택

- React 16.11.0
- React Router DOM 5.1.2
- React Transition Group 4.3.0

## 프로젝트 구조

```
src/
├── places/          # 장소 관련 컴포넌트
├── shared/          # 공통 컴포넌트 및 유틸리티
│   ├── components/  # UI 컴포넌트
│   ├── context/     # Context API
│   ├── hooks/       # Custom Hooks
│   └── util/        # 유틸리티 함수
└── user/            # 사용자 관련 컴포넌트
```

## 시작하기

1. 프로젝트 클론
```bash
git clone [repository-url]
```

2. 의존성 설치
```bash
npm install
```

3. 개발 서버 실행
```bash
npm start
```

## 사용 가능한 스크립트

- `npm start`: 개발 서버 실행
- `npm test`: 테스트 실행
- `npm run build`: 프로덕션용 빌드
- `npm run eject`: CRA 설정 추출

## 브라우저 지원

### 프로덕션 환경
- 점유율 0.2% 이상의 브라우저
- 지원 종료되지 않은 브라우저
- Opera Mini 제외

### 개발 환경
- Chrome 최신 버전
- Firefox 최신 버전
- Safari 최신 버전
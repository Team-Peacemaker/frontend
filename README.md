# LawHelper Frontend

> LawHelper는 법률 자문 챗봇 서비스입니다. 이 레포는 사용자가 챗봇과 상담하고, 변호사를 검색·추천받을 수 있는
> 웹 클라이언트를 담당합니다.

## 주요 기능

- **홈**: 추천 질문, 최근 상담 내역, 전문가(변호사) 추천을 한 화면에서 확인
- **검색**: 성범죄·재산범죄·교통사고 등 분야별 카테고리로 법률 상담 주제 탐색
- **채팅**: 세션 단위로 이어지는 챗봇과의 법률 상담 대화
- **변호사 상세/예약**: 변호사 프로필 확인 및 상담 예약
- **메시지함**: 상담·예약 관련 메시지 목록 확인
- **마이페이지**: 사용자 정보 및 상담 이력 관리

## 기술 스택

- React 19
- React Router
- Axios

## 실행 방법

```bash
npm install
npm start
```

`http://localhost:3000`에서 확인할 수 있습니다.

백엔드 API 서버는 [lawhelper_server](https://github.com/Team-Peacemaker/lawhelper_server)를 함께 실행해야 합니다.

# 🌟 StarCle Platform Demo

> **StarCle** (Startup Recycle) — 망한 스타트업의 디지털 자산(코드, 디자인)을 되살려 거래하는 플랫폼  
> 이 저장소는 StarCle의 데모와 오픈 가능한 UI/컴포넌트/프레임워크 리소스를 포함합니다.



## 🧩 소개

**StarCle Platform Demo**는 실제 서비스의 민감한 비즈니스 로직을 제외한 공개용 코드 기반입니다.  
디자이너, 개발자, 투자자에게 StarCle의 핵심 개념과 UI/UX 흐름을 보여주는 데 목적이 있습니다.



## 📁 구성

```
starcle-platform-demo/
├── app/                # Next.js App Router 기반 라우팅
├── components/         # 공통 UI 컴포넌트
├── demo/               # 자산 프리뷰 페이지 및 샘플 케이스
├── public/             # 정적 자산 (이미지 등)
├── styles/             # Tailwind 및 글로벌 스타일
├── types/              # 타입 정의
└── README.md
```

## 🛠️ 기술 스택

- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Forms & Validation**: React Hook Form, Zod (optional)
- **API Spec**: Swagger / OpenAPI (예정)



## 🚫 제외된 항목

이 저장소에는 다음과 같은 비공개 항목이 포함되지 않습니다:

- 인증 및 정산 로직
- 구매/거래 처리 백엔드
- 핵심 데이터베이스 연결
- 실제 자산 판매 모듈

이러한 로직은 `starcle-core` (비공개) 저장소에서 관리됩니다.


## 📄 라이선스

- 코드: [MIT License](./LICENSE)
- 디자인 및 샘플 자산: **비상업적 용도에 한해 사용 가능** (CC BY-NC 4.0, 별도 명시 예정)



## 📬 문의

StarCle 프로젝트에 관심이 있으시다면  
`dev.woojin.lee@gmail.com` 으로 연락 주세요.



**스타트업 자산, 다시 날아오르다. — StarCle 🚀**

# EasyTalk - 쉬운 말 변환 커뮤니케이션 애플리케이션

한국어의 어려운 단어나 복잡한 표현을 쉬운 말로 자동 변환해주는 AI 기반 웹 애플리케이션입니다.

## 🎯 주요 기능

### 관리자 모드 (EASY TALK / 1234)
- **GPT API 통합**: OpenAI GPT를 활용한 지능적 변환
- **AI 규칙 관리**: 어려운 단어 → 쉬운 단어 매핑 규칙 추가/삭제
- **난이도 조절**: 3단계 AI 똑똑함 레벨 설정
- **단어별 수정**: 변환 결과를 세밀하게 조정
- **데이터 관리**: 전체 학습 데이터 백업/초기화

### 게스트 모드 (guest / guest123)
- **텍스트 변환**: 어려운 말을 쉬운 말로 자동 변환
- **진짜 사전**: 19개 한국어 단어의 완전한 뜻풀이
- **단어 테스트**: 4지선다 퀴즈로 학습 확인
- **음성 기능**: 음성 인식/텍스트 읽기 지원

## 🚀 빠른 시작

### 1. 파일 다운로드
```bash
git clone https://github.com/your-username/EasyTalk.git
cd EasyTalk
```

### 2. 브라우저에서 실행
`index.html` 파일을 브라우저에서 열기

### 3. 로그인
- **관리자**: `EASY TALK` / `1234`
- **게스트**: `guest` / `guest123`

### 4. GPT API 설정 (선택사항)
1. [OpenAI API Keys](https://platform.openai.com/api-keys)에서 API 키 발급
2. 관리자 로그인 후 GPT API 설정 섹션에서 키 입력
3. 연결 테스트로 확인

## 📁 파일 구조
```
EasyTalk/
├── index.html          # 메인 HTML 파일
├── app.js              # 핵심 JavaScript 로직
├── README.md           # 프로젝트 설명서
├── .gitignore          # Git 무시 파일 목록
└── docs/
    └── screenshots/    # 스크린샷 폴더
```

## 🎮 사용 예시

### 기본 변환
```
입력: "협조 부탁드립니다 서류를 제출해 주시기 바랍니다"
출력: "도와주세요 서류를 내 주세요"
```

### GPT 통합 변환 (더 자연스러움)
```
입력: "귀하의 신청서를 검토하여 승인 여부를 결정하겠습니다"
출력: "당신의 신청서를 살펴보고 허락할지 정하겠습니다"
```

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **AI**: OpenAI GPT-3.5-turbo API
- **Storage**: LocalStorage (브라우저 저장소)
- **Audio**: Web Speech API

## 🔑 API 키 설정

### OpenAI API 키 발급
1. [OpenAI 홈페이지](https://platform.openai.com) 접속
2. 계정 생성 및 로그인
3. API Keys 메뉴 → "Create new secret key"
4. `sk-`로 시작하는 키 복사

### 애플리케이션에 설정
1. 관리자 모드로 로그인
2. "GPT API 설정" 섹션 찾기
3. API 키 입력 후 "API 키 저장"
4. "연결 테스트"로 정상 작동 확인

## 📊 변환 통계

- **기본 규칙**: 100+ 어려운 단어 매핑
- **AI 레벨**: 3단계 (기본/보통/고급)
- **사전 단어**: 19개 완전 설명
- **학습 능력**: 사용할수록 정확도 향상

## 🎨 주요 특징

### AI 기반 지능형 변환
- 문맥을 이해하는 GPT 통합
- 3단계 난이도별 어려운 단어 감지
- 받침 처리를 통한 자연스러운 조사 변환

### 사용자 친화적 UI/UX
- 직관적인 드래그 앤 드롭 디자인
- 실시간 음성 인식/재생
- 반응형 웹 디자인

### 학습 및 개선
- 사용자 피드백 기반 AI 학습
- 관리자 규칙 추가로 지속 개선
- 변환 히스토리 및 통계 제공

## 🔒 보안 및 개인정보

- **로컬 저장**: 모든 데이터는 사용자 브라우저에만 저장
- **API 키 보안**: API 키는 외부로 전송되지 않음
- **개인정보 없음**: 개인정보 수집하지 않음

## 🤝 기여 방법

1. Fork 프로젝트
2. Feature 브랜치 생성 (`git checkout -b feature/AmazingFeature`)
3. 변경사항 커밋 (`git commit -m 'Add some AmazingFeature'`)
4. 브랜치에 Push (`git push origin feature/AmazingFeature`)
5. Pull Request 생성

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 🙏 감사 인사

- OpenAI GPT API 제공
- Web Speech API 브라우저 지원
- 한국어 언어학 연구 자료

## 📞 문의

- **이슈**: [GitHub Issues](https://github.com/your-username/EasyTalk/issues)
- **기능 요청**: [GitHub Discussions](https://github.com/your-username/EasyTalk/discussions)

---

**EasyTalk**로 누구나 쉽게 이해할 수 있는 소통을 만들어보세요! 🎉

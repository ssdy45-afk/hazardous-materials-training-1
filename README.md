# 🛡️ 위험물 실무교육 포털 (Hazardous Materials Practical Training Portal)

> **위험물안전관리법 및 현장 공학 기준에 기반한 36개 전 과정 디지털 실무 교육 포털**  
> 직관적인 UI, 실시간 영상 시청 인증 게이트(90%), 단계별 실무 학습, 퀴즈 및 수료증 자동 발급 시스템을 제공합니다.

---

## ✨ 핵심 기능

1. **📚 36개 전 과정 커리큘럼 (1~6류 위험물, 시설/저장/취급/운반/소화/비상대응)**
   - **기초 단원 (1~12강)**: 위험물 성상(제1~6류), 저장·취급·시설·운반 기준, 소화설비 실무
   - **심화 단원 (13~24강)**: 일반취급소, 판매취급소, 옥외/지하탱크, 배관시설, 지정수량 합산, 인허가·검사
   - **실무 단원 (25~36강)**: 사업장 위험물 지도, SDS/GHS, 소분·정전기, Spill Kit 방재, 아차사고, 종합 모의훈련

2. **🎬 2종 필수 영상 동시 탑재 및 90% 게이트 타이머**
   - 탭 전환 없이 한 화면에서 **실제 사고사례/예방수칙 영상**과 **법령·실무 강의**를 동시 시청
   - 두 영상의 실제 길이를 초 단위로 정밀 계산하여 **합산 90% 이상 시청 시에만 확인 버튼 잠금 해제**
   - 한국소방안전원(KFSI), 안전보건공단(KOSHA), 소방청, 화학물질안전원 공식 영상 72종 100% 매칭

3. **📝 3대 학습 기둥 (Pillars)**
   - **기둥 1 (사고분석 & 소방실무)**: 실제 사례 기반 원인 분석 및 현장 재발방지대책
   - **기둥 2 (현장 기본수칙 Basic 01~05)**: 법적 요건, 기술기준, SOP, 이상감지 Stop-Work, 비상대응 롤콜
   - **기둥 3 (실무 단원 Unit 01~03)**: 공정 안전, 체크리스트, 비상 방재 실습

4. **🎓 수료증 발급 및 관리자 커스텀 에디터**
   - 퀴즈(4문항 중 3문항 이상 통과) 완료 시 수료증 즉시 발급
   - 관리자 모드에서 교육기관명, 직인 이미지, 안전관리자 서명, 수료번호 형식 자유 변경 및 인쇄/PDF 저장

---

## 🚀 GitHub Pages로 무료 웹 호스팅하는 방법

이 저장소의 `index.html`을 활용하면 별도 서버 구축 없이 GitHub에서 바로 무료 웹사이트로 오픈할 수 있습니다.

1. 저장소 상단의 **Settings** 메뉴로 이동합니다.
2. 좌측 메뉴에서 **Pages**를 클릭합니다.
3. **Branch** 설정에서 `main` (또는 `master`) 브랜치를 선택하고 `/ (root)` 폴더로 지정한 뒤 **Save**를 누릅니다.
4. 1~2분 후 생성되는 **`https://ssdy45-afk.github.io/hazardous-materials-training-1/`** 주소로 접속하시면 전 세계 어디서나 웹으로 교육을 진행하실 수 있습니다!

---

## 📂 파일 구조

```
├── index.html                    # 단일 파일 완결형 메인 웹 포털 (React + Babel + Tailwind CDN)
├── README.md                     # 프로젝트 설명서
├── logo.png                      # 공식 교육 로고
├── 위험물_실무교육_포털.html       # 로컬 실행용 독립형 포털 파일
└── bundle_data_36.json           # 36개 전체 과정 메타데이터 및 72개 영상 데이터셋
```

---

## 🛠️ 기술 스택

- **Frontend**: React 18, Babel Standalone, Lucide Icons, Canvas Confetti
- **Styling**: Tailwind CSS, Modern Glassmorphism CSS Design System
- **Video Integration**: YouTube Embedded Player with Dynamic Duration Tracking
- **Deployment**: Standalone Single HTML / GitHub Pages Compatible

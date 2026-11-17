# 🚰 하수관 관제일지 (Sewer Guard // Gradient Descent)

**프레디의 피자가게(FNAF) 스타일의 CCTV 관제 긴장감** + **오모리(OMORI) 헤드스페이스·화이트스페이스 감성의 16비트 픽셀 아트** + **경사하강법(Gradient Descent) AI 이상 탐지 퍼즐**을 결합한 Streamlit 웹 게임입니다.

## 📁 프로젝트 구조
```text
sewer_guard_streamlit/
├── app.py                  # Streamlit 메인 실행 파일
├── requirements.txt        # Python 패키지 의존성
├── README.md               # 프로젝트 안내 및 배포 가이드
├── .streamlit/
│   └── config.toml         # 오모리 테마(다크 퍼플·라벤더) 설정
└── assets/
    └── game_view.html      # 픽셀 아트 캔버스 렌더링 & 경사하강법 게임 엔진
```

## 🚀 로컬 실행 방법
```bash
pip install -r requirements.txt
streamlit run app.py
```

## ☁️ GitHub + Streamlit Community Cloud 배포 방법
1. 이 폴더의 모든 파일을 GitHub 새 저장소(Repository)에 업로드합니다.
2. [Streamlit Community Cloud](https://share.streamlit.io/)에 로그인한 뒤 **New app**을 클릭합니다.
3. 연결한 GitHub 저장소와 브랜치(`main`), 메인 파일 경로(`app.py`)를 선택하고 **Deploy!**를 누르면 즉시 웹 주소가 생성됩니다.

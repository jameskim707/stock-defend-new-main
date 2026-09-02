# GINI Guardian v4.6 Stable

감정적인 주식 과잉투자를 줄이기 위한 Streamlit 상담 도구입니다.

## 배포

1. 이 폴더 전체를 GitHub 저장소에 업로드합니다.
2. Streamlit Community Cloud에서 `app.py`를 실행 파일로 지정합니다.
3. 앱 설정의 Secrets에 아래 값을 등록합니다.

```toml
GROQ_API_KEY = "본인의 Groq API 키"
```

API 키를 GitHub 파일이나 `.streamlit/secrets.toml`에 직접 저장하지 마세요.

## 주의

- 투자 수익을 예측하거나 매수·매도를 권유하는 앱이 아닙니다.
- 포트폴리오 가격은 pykrx가 제공하는 최근 거래일 종가이며 실시간 체결가가 아닙니다.
- 가격 조회에 실패하면 임의 가격을 만들어 표시하지 않습니다.

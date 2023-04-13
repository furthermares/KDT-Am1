# Monthly1_1

1. requirements.txt를 먼저 실행시켜서 필요한 라이브러리 준비
2. train_word_embedding.py를 실행 전, 아래 링크에서 훈련데이터를 먼저 받아서 로컬에 저장
  glove.6B.zip을 다운받으면 됩니다.
  [word2vec 사전 훈련 데이터](https://nlp.stanford.edu/projects/glove/)
3. API를 신청 후, './streamlit/secrets.toml'에 'OPEN_API_KEY="발급받은 API"'를 생성
  [Steamlit OPEN API](https://medium.com/@avra42/summarizing-scientific-articles-with-openai-and-streamlit-fdee12aa1a2b)
4. `streamlit run test_streamlit.py` 로 실행

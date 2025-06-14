# 사용예시

from textminer import remove_stopwords, extract_keywords, summarize_text, detect_language

text = "OSS 수업은 정말 즐거웠습니다."

# 불용어 제거
print(remove_stopwords(text, lang="english"))

# 키워드 추출
print(extract_keywords(text))

# 텍스트 요약
print(summarize_text(text))

# 언어 감지
print(detect_language(text))


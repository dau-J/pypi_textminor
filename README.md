
# pypi_textminor
pypi 라이브러리 텍스트마이닝 프로그램

textminer-pro
A Korean-friendly text preprocessing toolkit that supports:

remove_stopwords(text, lang='en')
extract_keywords(text, top_n=5)
summarize_text(text, ratio=0.2)
detect_language(text)

## pypi패키지 링크 및 사진
pypi패키지 링크 [https://pypi.org/project/textminerpro-hyeonsung/]
--------------------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/1d0adada-88e6-43da-8bb1-c1be6be1c624)




## 📁 프로젝트 폴더 구조
------------------------------------------------------------------------------------------------

```
textminer_pro/
├── textminer/                   
│   ├── __init__.py              
│   ├── cleaner.py               
│   ├── summarizer.py            
│   └── detector.py              
│
├── tests/                       
│   ├── test_cleaner.py          
│   └── test_detector.py         
│
├── setup.py                     
├── README.md                    
└── .github/                     
    └── workflows/
        └── pypi.yml             
```



### 기능

* **텍스트 정제:** 불용어를 효율적으로 제거하고 다른 텍스트 정규화 작업을 수행합니다.
* **텍스트 요약:** 긴 텍스트의 간결한 요약을 생성합니다.
* **언어 감지:** 주어진 텍스트의 언어를 자동으로 식별합니다.

### 설치

pip를 통해 TextMiner Pro를 설치할 수 있습니다.

```bash
pip install textminerpro-hyeonsung==0.0.1

# Service_data_science

## 기획 서비스 
컨텐츠 기반 필터링을 사용한 반려식물 추천 서비스(어플)
## 기획 목적
반려 식물의 입문자에게 느껴질 수 있는 진입 장벽을 낮춰줄 뿐만 아니라 반려식물을 선택하고자 하는 모든 사람들에게 환경과 취향에 따라 더욱 맞춤화된 반려식물 추천

## 컨텐츠 기반 필터링
해당 프로젝트에서 컨텐츠 기반 필터링 구현을 맡음
### 개발 환경
- IDE : 주피터노트북
- Programming language : Python
- Library : Requests, Beautifulsoup, urllib.request, pandas, numpy, sklearn.cosine_similarity
### 파일 설명
- crawler.ipynb : 농사로 홈페이지에서 크롤링한 잎 관상 식물과 건조 식물의 특성 데이터 수집 코드
- model_code.zip
    - plantsDB1 : 카테고리화 마친 잎 관상 식물 데이터
    - plantsDB2 : 카테고리화 마친 건조 식물 데이터
    - pre_data : 잎 관상 식물 특성 설명 데이터
    - pre_data2 : 건조 식물 특성 설명 데이터 
    - model final : 컨텐츠 기반 필터링 구현 코드

## flutter 사용한 어플 제작
### 개발 환경
- IDE : Android Studio
- Programming language : Dart
- Tools : Firebase

### 파일
파일 : https://drive.google.com/file/d/1t7HaeJxHTpOMvNHqclX-F86UU-TLqOZV/view?usp=sharing
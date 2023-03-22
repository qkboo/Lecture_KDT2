# Data crawling

<!--1. 크롤링 시작
    - [데이터크롤링1-01HTTP사용, HTTPS상황](notebooks/데이터크롤링1-01HTTP사용_HTTPS상황.ipynb)
    - [데이터크롤링1-03BS4_Start.ipynb](notebooks/데이터크롤링1-03BS4_Start.ipynb)
    - [실습-유튜브-랭킹](notebooks/실습-유튜브-A.ipynb) -->


# 1. Web 기본
   - HTTP 이해:  HTTP / HTML / CSS / MIME Type
      - 참고자료: `크롤링참고-HTTP이해(발췌,자바를다루는기술).pdf`
   - 강의중 노트: [Webcrawling_HTTP_HTML.ipynb](notebooks/데이터크롤링1-00HTTP_HTML.ipynb)

# 2. Python 네트워크 (http)
   - requests 모듈: [데이터크롤링1-02requests.ipynb](notebooks/데이터크롤링1-02requests-0.ipynb)
   - Beautifulsoup 모듈: [데이터크롤링1-03BS4_Start.ipynb](notebooks/데이터크롤링1-03BS4_Start-0.ipynb)

# 3. 파일 저장

CSV 파일 읽고/쓰기:
   - https://docs.python.org/ko/3/library/csv.html
   - https://wikidocs.net/80822
   - Sample file:
       - https://github.com/UCLSPP/datasets/blob/master/data/Credit.csv

JSON 파일 읽고/쓰기:
   - https://wikidocs.net/67980 
   - json 쓰기: https://wikidocs.net/126088

# "실습": 네이버 상영자/예정작 크롤링 결과 csv 저장

1. 제목 / { 네티즌 평점/참여 인원 } / {기자 평점 / 인원 } / 감독 / 출연진 / 개봉일
1. `함수` 적용해 보세요
1. **완료시** 과제폴더 오늘날자에 `이름_영화상영작_csv.ipynb` 형식으로 업로드.

<!--
수업중 실습: 네이버 영화랭킹 날짜별 출력 [실습_크롤링_영화랭킹_1122.md](notebooks/실습_크롤링_영화랭킹_1122.md)
**결과 샘플**: [김예원_상영작_csv_test.ipynb](notebooks/김예원_상영작_csv_test.ipynb)

-->

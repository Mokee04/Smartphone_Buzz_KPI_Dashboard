# Smartphone_Buzz_KPI_Dashboard

---
 **2023 스마트폰 브랜드 S의 국가별 KPI 샘플 대시보드**

---
* 프로젝트 개요
  - 스마트폰 관련 기사 수집 데이터를 가공하여, 2023년도 S 브랜드의 스마트폰 Buzz KPI 현황을 확인할 수 있는 대시보드 구축하기
  - Python과 MySQL을 활용해 데이터를 생성 후 가공하고, 태블로로 대시보드 구축
  - pymySQL 라이브러리를 활용해 Jupyter Notebook 환경에서 MySQL DB에 접속 후, SQL 쿼리로 데이터 가공

* 활용 도구
  - Python
  - MySQL
  - Tableau
  
---
* 파일 설명

  (1) **Generating_Rawdata_v1.ipynb**
      : 스마트폰 관련 기사 수집 데이터(로데이터)를 생성합니다.
  
  (2) **Processing_KPI_v1.ipynb**
      : PyMySQL 라이브러리, Pandas와 MySQL 쿼리를 활용해 로데이터로부터 연 & 분기 단위 KPI를 집계한 테이블을 만듭니다.
  
  (3) **SMPBUZZ_KPI_Yearly & Quarterly_v1.twb**
      : 연 & 분기 단위 KPI 테이블을 활용해, 2023 S 브랜드 국가별 스마트폰 KPI 대시보드를 구축합니다.

---
* 로데이터 예시<br><br>
![image](https://github.com/Mokee04/Smartphone_Buzz_KPI_Dashboard/assets/66994825/c6da7b3f-1784-4bfb-8087-3820149fb774)

  - 컬럼 설명
     - Country : 기사가 발행된 국가 (예) 'United States'
     - Country_Code : 기사가 발행된 국가의 코드명
     - Date : 기사가 발행된 날짜
     - Weekday : 기사가 발행된 요일
     - Domain : 기사가 발행된 사이트명(무작위 생성된 회사명)
     - Headline : 기사 제목(무작위 생성된 텍스트)
     - Brand : 기사에서 언급된 모바일 브랜드 리스트
     - Product : 기사에서 언급한 모바일 제품
     - Topic : 기사 주제 review / issue / release / promotion
     - Tone : 기사 어조 positive / neutral / negative

     
* 샘플 대시보드 작업 결과

![지역별 대시보드_포폴_20240419](https://github.com/Mokee04/Smartphone_Buzz_KPI_Dashboard/assets/66994825/d8160b8a-3e6d-4cf0-90b1-5e94591b0532)


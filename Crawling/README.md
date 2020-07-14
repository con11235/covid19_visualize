## 어플 크롤링

* 크롤링 업무 분담
- 승혜: 앱 관련 장르 및 정보 크롤링
- 민정: 기간별 앱 순위 및 2020 매출 순위 크롤링

크롤링 사이트: [mobileindex](https://www.mobileindex.com/app/rank.asp)

### 기간별 앱 순위 크롤링 by 민정
* 2019-01-01 ~ 2019-06-01 6개월간의 매달 1일의 데이터, 2020-01-01~2020-06-01 6개월 간의 매달 1일의 데이터를 크롤링
* 앱 순위는 무료, 유료 순위로 구분되어있으며 2020년도의 경우에는 매출 순위도 추가되어있다.
* 또한 Google Play Store과 App Store로 구분되어있다.

따라서 play store와 app store로 크게 나누고, 그 안에서 기간별 무료 순위, 기간별 유료 순위, 2020 매출 순위로 나누었다.

[csv 데이터 설명]  
- app_sales_rank_appstore.csv : App Store의 매출 순위 2020
- app_sales_rank_playstore.csv: Play Store의 매출 순위 2020
- appRank_free_appstore.csv : App Store의 2019 ~ 2020 기간별 무료 어플 순위
- appRank_free_playstore.csv : Play Store의 2019 ~ 2020 기간별 무료 어플 순위
- appRank_pay_playstore.csv : Play Store의 2019 ~ 2020 기간별 유료 어플 순위
- appRank_pay_appstore.csv : App Store의 2019 ~ 2020 기간별 유료 어플 순위


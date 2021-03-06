# 2019학년도 교육용 소프트웨어 페스티발
![posetr](https://github.com/kyu9341/Python-Movie-Recommendation/blob/master/pictures/poster.png)

## 행사기간  
2019.11.11(월) ~ 11.15(금)  

## 접수기간  
2019.10.14(월) ~ 10.31(목)  

## 작품모집 분야  

- SW 기초 교양교육용 언어로 개발된 모든 SW 작품 (스크래치, 파이썬)
- 수업결과물에 의한 SW 작품
- 개인 및 팀에 의해 개발된 SW 작품으로 전공자(공학) 및 비전공자를 구분하여 출품
- 개인 및 팀에 여러 개의 다른 작품 출품 가능  

## 진행방향  

10.31(목) 까지 파이썬을 이용한 SW를 제작한다.  

3인 팀을 구성하여 참여하며 3인 모두 전공자(공학)이다.  

파이썬을 이용하여 영화 리뷰 데이터를 시각적인 부분을 살려 영화를 보기 전 영화에 대한 정보를 얻을 수 있고 영화의 수준을 파악 할 수 있다.  

이후 머신러닝을 적용하여 영화 추천 기능을 제작한다.

## 개발 목표
- 파이썬 웹 크롤링을 통한 인기 영화 정보 수집 및 댓글 워드 클라우드화
- Django를 통해 웹 서버 및 UI 제공 (영화 별 상세정보 및 워드 클라우드 출력)

## 개발 내용
파이썬 라이브러리인 Beautiful Soup을 사용하여 네이버 영화의 각 영화별 정보 및 댓글을 수집한다. 수집한 영화의 댓글을 영화의 포스터의 모양과 색상에 맞게 워드 클라우드로 제작하며 이 모든 과정을 자동화한다. 이 후 파이썬 웹 프레임워크인 Django와 Mysql 데이터베이스를 통해 벡엔드 및 간단한 프론트 엔드 환경을 구축하며 각 영화 별로 수집된 폴더에 접근하여 파일화 된 데이터들을 읽어와 가공하여 데이터베이스에 저장한다. 

사용자에게는 검색창과 저장된 영화 리스트를 제공하며 검색 또는 리스트 선택 시 선택된 영화의 상세정보 화면으로 이동하며 포스터 및 여러 가지 영화 정보, 수집된 많은 댓글로 제작된 워드 클라우드를 출력시킨다. 이를 통해 한 눈에 다른 관람객들이 어떤 단어들을 이용하여 영화에 댓글을 남겼는지 확인할 수 있도록 한다.

프로그램 시연시간 감소를 위해 미리 50여개의 영화 데이터를 제작해 두었으며 이후 웹호스팅이 시작되면 영화의 정보와 리뷰 크롤링 및 워드클라우드 제작이 모두 자동화가 가능하다.

## 기대 효과
영화를 보기 전 웹을 들어가서 줄거리와 워드클라우드, 평점 등을 열람할 수 있으며 워드클라우드를 보고 해당 영화의 분위기와 느낌을 알 수 있으며 자신과 맞는 영화인지를 스포일러를 보지 않고 파악할 수 있다.

## 데모 화면
![movie1](https://github.com/kyu9341/Python-Movie-Recommendation/blob/master/pictures/moviecloud.png)

![movie2](https://github.com/kyu9341/Python-Movie-Recommendation/blob/master/pictures/moviecloud2.png)

![movie3](https://github.com/kyu9341/Python-Movie-Recommendation/blob/master/pictures/moviecloud3.png)

## 결과
![posetr](https://github.com/kyu9341/Python-Movie-Recommendation/blob/master/pictures/award.png)




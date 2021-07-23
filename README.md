# Movie_Recommendations

--------------------------
# Overview
* Organization : None
* Project Title : 영화 추천 시스템 구현
* Project Description : 추천 알고리즘별 영화 추천 시스템 구현
* Author : 황규희
* Date : 2021.07.20 - 2021.07.25
--------------------------
# Dataset
* [the-movies-dataset | kaggle](https://www.kaggle.com/rounakbanik/the-movies-dataset)
--------------------------
# Recommendation algorithm
## Contents Based Filtering
* 사용자와 아이템에 대해 DB를 구성하여 이를 기반으로 추천하는 방법
* 데이터 셋을 구성하기 매우 어려움
* 수작업 입력과 DB를 설계하는 일에 인력이 많이 소요됨 
  ### user-based recommendation
  * 사용자에 대한 정보(성별, 나이대, 지역, ...)를 기반으로 DB를 구성하고 비슷한 사용자의 선호 영화를 추천하는 방식
  ### item-based recommendation
  * 영화에 대한 정보(장르, 출연 배우, ...)를 기반으로 DB를 구성하고 비슷한 영화를 좋아했던 사용자에게 비슷한 영화를 추천하는 방식
## Collaborative Filtering
* 사용자의 과거 행동 양식을 기반으로 추천하는 방법
## Latent Factorization

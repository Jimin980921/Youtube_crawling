## Youtube 데이터분석  
__유행에 민감한 Youtube를 크롤링하여 유행음식 분석 및 시각화__  
> 유튜브는 유행이 즉각적으로 드러나고, 유튜브의 댓글에서 시청자의 반응이나 감정이 잘 들어나는 특징이 있음  
<br>


-------------------------------------------------------------------------------------------------------------------
## 개발 환경  
* BeautifulSoup, selenium, chromeWebDriver, Jupyter Notebook 사용

* hadoop, spark, python3 사용

* __데이터 수집방법__: 구독자 수가 10만명이상되는 유튜버들의 먹방 정보 수집  
<br>



## 개발단계  
__1단계: 데이터 수집__ -구독자 20만이상 유튜버 50명의 먹방동영상 정보 크롤링  
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/90315013-ed505a80-df52-11ea-8f89-30286916d3d9.JPG" width=45%>
</p>  
<br>




__2단계: 데이터 전처리__ - 50명의 유튜버의 먹방 제목 불용어 제거, 동의어 처리    
 __불용어제거 전__ |  __불용어제거 후__ |
:------------------------------------:|:-------------------------:|
![](https://user-images.githubusercontent.com/57060127/95224218-62465f00-0835-11eb-9033-46cd89f33766.JPG)  |  ![](https://user-images.githubusercontent.com/57060127/95224226-64102280-0835-11eb-83b2-2f22a341e334.JPG)  |
<br>


__3단계: 데이터 분석__ - 정제된 데이터 빈도분석  
<p align="center">
<img src="https://user-images.githubusercontent.com/57060127/95223415-8190bc80-0834-11eb-8f5b-dcb547c0e90f.JPG" width=70%>  
</p>
<br>

-------------------------------------------------------------------------------------

## 분석 결과  
> 프로젝트시기에 유행했던 불닭볶음면, 치즈볼, 당면 등의 빈도수가 높은 것으로 도출
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/76674502-891c1a00-65f3-11ea-9062-1f7cc7cc43d2.PNG" width=40%>
</p>
<br>
<br>



- 유사 프로젝트  
   - [네이버 쇼핑 리뷰 크롤링 프로젝트](https://github.com/Jimin980921/text_mining)  
   - [네이버 지도 크롤링 ](https://github.com/Jimin980921/Dongjak_bigdata_project) 



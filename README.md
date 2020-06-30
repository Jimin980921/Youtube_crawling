# crawling
* __목표__: 유튜브는 유행이 즉각적으로 드러나고, 유튜브의 댓글에서 시청자의 반응이나 감정이 직접적으로 드러나는 편이다. 정제되지않고 솔직한 raw data들이 많은 유튜브를 크롤링하고 싶었다. 본 프로젝트는 유튜브에서 인기가 많은 youtube 먹방 크롤링 후, 어떤 음식의 빈도수가 높은지 시각화하여 유행분석 및 인기음식을 알아보았다. 


-------------------------------------------------------------------------------------------------------------------
* BeautifulSoup, selenium, chromeWebDriver, Jupyter Notebook 사용

* hadoop, spark, python3 사용

* __데이터 수집방법__: 구독자 수가 10만명이상되는 유튜버들의 먹방 제목을 자동 스크롤을 하여 처음부터 끝까지 가져온다.

* __데이터 처리__: 약 50명의 유튜버의 먹방 제목 불용어 제거, 동의어 처리 후 빈도수 추출
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/85222662-fd870600-b3f7-11ea-91e6-06901055d920.JPG" width=80%>
</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/85222664-ff50c980-b3f7-11ea-8009-f54fac3f79eb.JPG" width=80%>
</p>
<br>
<br>


* __데이터 후처리__: 각 유튜버 먹방 제목의 빈도수 추출한 txt를 합쳐서 FrequencyRdd를 만든다. 그 후 음식이름을 기준으로 빈도수를 더해 겹치는 단어의 빈도수를 합한다. 

* __결과__: 
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/76674502-891c1a00-65f3-11ea-9062-1f7cc7cc43d2.PNG" width=40%>
</p>

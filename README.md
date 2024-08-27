# MediaTrip_data
 
## ⚡기획의도⚡
**미디어 촬영지** 의 데이터를 토대로<br/><br/>
**장소의 정보**를 지도로 확인하자 <br/><br/>

## ✌데이터셋 정보✌
해당 데이터는<br/>
[문화 빅데이터 플랫폼](https://www.bigdata-culture.kr/bigdata/user/data_market/detail.do?id=462fe230-0334-11ee-a67e-69239d37dfae, '문화 빅데이터 플랫폼')에서 내려받았으며 <br/>
'한국 문화 정보원'에서 제공한 '미디어콘텐츠 영상 내 유명지 데이터'를 사용하였습니다<br/>
이후 Jupyter notebook을 통해 데이터 가공하였습니다<br/><br/>

## 👍데이터 가공 과정👍

+ 일단 필요없는 데이터는 **삭제처리** 하였고<br/>
+ 영어로 적힌 데이터값(cafe, restaurant, playground 등등)을 **한글로 변환** 하였으며<br/>
+ 주소의 경우<br/>
++ 서울과 서울특별시, 서울 특별시 등, 부산과 부산광역시, 경기도와 경기 등<br/>
++ **이중등록**되어있는 경우가 있어 모두 **통일** 시키고 **변환**함<br/>
    
## ✔가공 후 이슈✔
데이터 가공 이후 API테스트, 안드로이드 작업 과정에서<br/>
모두 통일 되었다고 생각되었는데 DB 작업도중 잘못 표기된 주소들이 많이 발견되어 재수정함<br/>
추가로 위도경도가 잘못 기입된 장소들이 있어 수정함<br/><br/>

## 🎈결과🎈
만들어진 데이터파일로 서버와 안드로이드 개발을 진행함<br/>
[서버 깃허브 링크](https://github.com/spiegelgo/aws-media-server, '서버 깃허브 링크')<br/>
[안드로이드 깃허브 링크](https://github.com/spiegelgo/MediaTrip_android, '안드로이드 깃허브 링크')<br/>
[프로젝트 기술서 링크](https://docs.google.com/presentation/d/1LXr1Qc0jYfgcrlqNZCiGHb6zWxD_4zUnYdpqZs3dbVc/edit?usp=sharing, '프로젝트 기술서 링크')<br/>
[시연 동영상 링크](https://youtu.be/cTmRnp7LIYM, '시연동영상 링크')<br/>

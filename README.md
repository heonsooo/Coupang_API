# Coupang_API
쿠팡_API 활용


- 쿠팡파트너스 API를 활용합니다.

#### cp_url.py
- 쿠팡파트너스 API를 이용해 원하는 키워드의 100개 항목이 있는 URL을 얻습니다.

#### cp.py
- 쿠팡파트너스 API를 이용해 원하는 키워드의 상위 제품 N개를 저장합니다.

***

#### 왜 쿠팡 파트너스 API를 사용하였는가?

1. 이전에 조코딩-주식 자동 트레이딩 파이썬을 구현 후 잠깐의 시간을 투자해        
   패시브 수입이 생길 수 있는 자동화 파이프라인을 만들면 좋겠다고 생각했습니다. 

2. 그렇게 네이버 쇼핑에서 인기 제품들을 쿠팡 파트너스에서 검색 후 블로그에 포스팅하는 시스템을 생각했습니다.  
   (네이버 쇼핑 - TOP100에서 상위 10개 제품 키워드 추출 성공 - https://github.com/heonsooo/Project_Crawling/blob/main/naver_shop10.py)     

3. 쿠팡 파트너스 홈페이지에서 셀레늄을 통해 제품을 파싱 해오려고 했지만,           
   크롬 드라이버로 쿠팡 파트너스에는 **무한 로딩**이 되며 로그인이 되지 않았습니다. --- 문제점 1)   

4. 방법을 찾던 중 **쿠팡 파트너스 API**가 있는 것을 확인 후 아이디, 비밀번호 키를 발급받았습니다. --- 해결 1)


#### 쿠팡파트너스 API는 유용한가?  
1. 유용합니다. 하나하나의 제품을 가져오지 않고,  
   특정 키워드를 입력 혹은 특정 URL을 입력하면 판매 제품들을 각 태그별로 반환해 줍니다.  

2. 하지만 1시간에 10회 호출 제한이 걸려있어 유의하여 사용해야 합니다.    
   ~~(제대로 작동하는지 확인하며 코드 수정하다 10회 초과 호출로 24시간 제재를 받았습니다.)~~ 
      
#### 무엇을 얻었는가 ? 

1. API 사용에 막연한 두려움이 있었지만, 이 장벽에 대해 사다리를 타고 올라갈 만큼은 용기가 생겼다.   
   (야,너두 할 수 있어)   
        
2. 물론 아직 완벽한 코드 구현은 하지 못하지만, 참고하여 원하는 기능을 구현할 수 있다.   
   
3.  쿠팡파트너스 API를 통해 티스토리 포스팅도 성공했다.    
   ~~(티스토리에서 이 행위에 대해 제재하는지 모르고 있었고, 이로 인해 유입이 없어 수입 달성은 어렵습니다.)~~  
   
   
## 결론
- 쿠팡파트너스API와 티스티로 API 사용으로 API 사용에 도전을 시작했다. 
- 하지만, 쿠팡파트너스 티스토리 자동 포스팅은 티스토리의 정책 위반이다.
- 수많은 API가 있으니 어서 빨리 다양한 프로젝트를 진행하고 싶다.
- 이 프로젝트의 기간은 약 일주일이 걸렸다. (2021-01-09 ~ 2021-01-14)

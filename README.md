# sw_contest

## Hallym SW Week 아이디어 공모전 심신안정팀


● **팀명** : 심신안정

● **팀원 및 역할**
   신유승 : 아이디어 제시, 기능 구현 정보 및 발표 프레젠테이션 제작 
   심보석 : 아이디어 제시, 기능 구현 정보 및 아이디어 발표
 

# 요약

● **프로젝트명** : 너의 목소리가 보여(Show Me Your Voice)

● **사용자의 음역대에 딱 맞는 노래 추천 리스트를 제공해주는 모바일 앱 서비스**

     대부분의 사람들은 고음을 잘해야 노래를 잘 부른다고 여기고 고음을 잘 내는 데에 급급한 경우가 많습니다.
     노래를 부르는 데 있어서 자신의 음역대에 맞게 부르는 것이 중요합니다.
     <너의 목소리가 보여>는 사용자의 목소리를 인식하고 그 음성을 측정하여 음역대를 제공하고 사용자의 음역대에
     딱 맞는 노래 추천 리스트를 제공해줍니다.
     
     
● **아이디어 독창성 및 파급효과**

  기존 시장에 존재하는 음악을 찾아주는 기술과 다르게 자신의 목소리에 맞는 노래들을 찾아주는 기술로
  차별성을 가지고 있습니다.
  
  모바일 앱 서비스에서 더 나아가 노래방에 설치된 키오스크를 통해 노래방을 방문한 사람들에게도 서비스를
  제공할 수 있습니다.
  
  
  
● **아이디어 배경**

- 노래 실력을 키우고 싶은 사람
- 노래방을 즐기는 사람
- 음이탈을 걱정하는 사람
- 부르기 쉬운 노래를 찾는 사람

자신의 음역대를 잘 알면 자신의 목소리에 맞는 노래를 찾을 수 있고 노래를 본인에게 맞는 키로 조절해서 부를 수 
있을 것이라는 생각에서 시작했습니다.



● **아이디어 기능 구현 <오픈 소스 활용>**

사용자의 육성이나 허밍(Humming)을 분석하여 음의 정보를 추출하는 오픈 소스인 PitchDection(피치 검출) 알고리즘을 사용함
추출된 음의 정보와 매칭할 음악 데이터는 크롤링(Crawling)과 스크래핑(Scrapping) 기법을 통해 음악 리스트를 가져와 DB에 저장함 
(크롤링과 스크래핑은 웹크롤링할 때 사용하는 Python 라이브러리인 BeautifulSoup을 사용함)
추출된 음의 정보와 데이터 베이스에 저장된 음악 파일은 KMP 알고리즘(스트링 매칭)을 통해 검색하여 사용자에게 제공함


● **기능 소개**

  - 어플을 통해 음역대를 측정하고 음역대에 맞는 노래 추천 리스트를 제공하는 기능이다.
  - 시작하기 버튼을 눌러 시작하면 가이드 음에 따라 음역대를 테스트한다.
  - 측정된 사용자의 음역대를 알려주고 그에 맞는 음역대의 노래 리스트를 추천해준다.
  - 추천된 노래 리스트는 플레이 버튼을 통해 들을 수 있는 음악 스트리밍 서비스도 제공할 수 있다.
  - 사용자의 음역대보다 높은 노래 또는 낮은 노래 또한 추천하여 제공할 수 있다.



● **아이디어 시장성**

기존 시장에 존재하는 음악 플랫폼 서비스와는 차별화된 나의 목소리에 맞는 음역대 찾기 프로그램을 통해 충분한 경쟁력을 가지고 있다고 생각한다. 더 나아가 모바일 앱 서비스로 우리만의 하나의 플랫폼 서비스 구축도 가능하고 기존에 있는 음악 플랫폼 서비스에 이 프로그램을 제공하여 시장의 상용화를 이룰 수도 있다.




  

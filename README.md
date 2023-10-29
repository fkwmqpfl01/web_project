# web_project

### 서비스 소개
오늘의 날씨 정보와 환율 정보를 활용해서 ‘오늘의 정보 조회하기’라는 서비스를 구현하였습니다. 동네예보조회서비스의 초단기 실황 조회 api를 사용하여 날씨 정보를 얻어오고, api manana를 활용하여 환율 정보를 얻어와 이를 표로 정리한 데이터를 보여주는 방식입니다. 간단한 내용의 서비스이지만 자기소개페이지, open api를 이용한 table 표 만들기 등 학습 내용을 적극 이용할 수 있었기 때문에 이 주제를 선정하여 진행하였습니다. 
### 변경 로그 요약

### 설치 방법
code.html 파일을 실행 시 서비스를 이용하실 수 있습니다.
### 기본 사용 예시
사용 시나리오는 간단합니다.  
  
우선적으로 오늘의 날씨 조회하기(section1)에서 값을 알맞게 입력 후 버튼을 누르면 날씨에 관한 정보가 table로 표시됩니다. 값을 입력할 때 입력 값이 없거나 길이가 다르게 입력될 경우 알림 창을 통해 오류를 알려주게 됩니다.  
  
또, section2 에서는 오늘의 날씨 조회하기에서 정보를 받아올 때 table에 나타나게 되는 자료 구분 코드 값에 대한 정보를 추가로 제공하게 됩니다. 기본적으로 table을 통해 한 눈에 알아볼 수 있도록 정리를 해서 제공하지만, 하나씩 검색해볼 수 있는 기능 또한 input 영역을 이용해 구성해보았습니다.  
  
Section3의 경우 환율 정보를 나타내었습니다. 오늘의 날씨 조회하기와 마찬가지의 방식으로 api의 데이터를 받아와서 table로 나타내주는 코드를 작성하였습니다. 다만, 다른 점은 이 api의 경우 다른 입력 값이 없어도 실시간에 맞는 값을 출력해주기 때문에 버튼 하나만으로 창을 구성하였습니다. 버튼을 누르게 되면 그에 맞는 데이터를 표로 볼 수 있는 것입니다.  
  
추가적으로 구현한 기능은 navigation기능입니다. navigation을 가로로 배치하는 방식을 학습하였는데, 이번 프로젝트를 하면서는 세로로 구성하는 방법을 생각했고 여러가지 style을 통해 이를 구현해보았습니다. 실제 프로젝트에서 Section을 나누면서 페이지의 길이가 길기 때문에 side에 위치한 nav가 유용하게 사용될 것으로 생각합니다. 각각의 navigation를 누르게 되면 section 순서대로 위치가 이동하는 모습을 볼 수 있습니다.   
### 문제 해결 단계
### 심화 자료와 문서 링크
### 변경 로그 소개
### 코드 유지 관리자
### 라이선스 정보

# 221205
참고사이트>>
IDE - 통합 개발 환경
https://www.hrd.go.kr/hrdp/ma/pmmao/newIndexRenewal.do - 직업훈련포털

api이용해서 부산날씨띄우기
=====================================
> const getJSON = function (url, callback) {<br>
  const xhr = new XMLHttpRequest();<br>
  xhr.open('GET', url, true);<br>
  xhr.responseType = 'json';<br>
  xhr.onload = function () {<br>
    const status = xhr.status;<br>
    if (status === 200) {<br>
      callback(null, xhr.response);<br>
    } else {<br>
      callback(status, xhr.response);<br>
    }<br>
  };<br>
  xhr.send();<br>
};<br>
  
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fpacksunjun%2F221205&count_bg=%23C8C83D&title_bg=%23FF0000&icon=riseup.svg&icon_color=%230070FF&title=%EC%A1%B0%ED%9A%8C%EC%88%98&edge_flat=true)](https://hits.seeyoufarm.com)<br>
![1](https://user-images.githubusercontent.com/112832753/206888655-57bee08c-eb55-4d09-961a-aa149b42b0ed.PNG)
1. API란

API란 Application Programming Interface의 약자로 프로그램이나 어플리케이션이 정보처리를 위해 운영체제에 호출하는 함수나 서브루틴의 집합을 말합니다. 서버에서는 API를 제공함으로써 클라이언트가 손쉽게 원하는 정보를 가져갈 수 있도록 도와줍니다. 
 
Web에서 데이터를 읽기 위해 사용되는 API는 좀 더 자세히 말하자면 RESTful API(Representational State Transfer-ful API)라고 하며

httpRequest를 통해 JSON이나 XML형식의 데이터를 읽어오게 됩니다.

웹프로토콜을 준수하여 데이터를 읽어오며, OrangeBoard WiFi+에서도 GET/POST를 주로 사용해 데이터를 읽어옵니다.

여러 웹사이트들은 이런 RESTful API를 제공하고 있으며 API를 통해 제공되는 데이터는 수천 수만가지로 다양하게 존재합니다.

만약에 예를 들어 어떤 특정한 지역의 교통정보를 알고 싶다면 교통 정보API를 가져와서 정보를 입력만 한다면 교통정보를 받아올 수 있습니다
식당으로 비유하자면 고객(클라이언트)이 부엌(서버)에서 원하는 요리(데이터)를 주문하기 위해 웨이터(API)를 불러 쉽게 주문하는 것을 생각하면 됩니다.
렌더링 - 서버로부터 HTML 파일을 받아 브라우저에 뿌려주는 과정
 DOM 트리와 CSSOM을 결합하여 렌더링 트리를 형성
과정-
HTML을 파싱하여 DOM 트리를 만든다.
CSS를 파싱하여 CSSOM 트리를 만든다.
DOM 과 CSSOM 을 결합하여 렌더링 트리를 만든다.
렌더링 트리에서 각 노드의 크기와 위치를 계산한다.
개별 노드를 화면에 그린다.

window는 BOM에 포함되어있고 document는 window에 포함

10장 6쪽 용어암기
alt + D 윈도우주소창검색


URI는 Uniform Resource Identifier, 통합 자원 식별자의 줄임말이다.
URL은 Uniform Resource Locator의 줄임말이다.
URN은 (Uniform Resource Name)의 줄임말이다.

myWin 이름의 윈도우가 열려 있지 않는 경우
	버튼을 클릭하면, myWin이름의 새 윈도우 열고 네이버 출력
myWin 이름의 윈도우가 이미 열려 있는 경우
	버튼을 클릭하면, 이미 열려있는 myWin이름의 윈도우에 네이버 출력

setTimeout() :  타임아웃 코드 1회 실행
setInterval() : 타임아웃 코드 반복 실행
msec - 초
웹 페이지 스크롤
윈도우 위치 및 크기 조절

onbeforeprint와 onafterprint

navigator 객체
screen 객체
history 객체

# NaverScrapper_202110

이 프로젝트는 데이터 수집을 위한 샘플 프로젝트로 네이버 카페 게임 섹션의 급상승 Top100 리스트와 실시간 Top100 리스트를 비교, 두 리스트에 공통으로 포함된 카페들의 데이터를 추출합니다.

파이썬 기반 자유 및 오픈 소스 웹 프레임워크 , 주피터 노트북을 사용해 구축된 프로젝트

## Getting Started 
### Dependencies 
* Python3.8 + 
* beautifulsoup4 == 4.6.0
* selenium == 3.141.0
* pandas == 1.2.4
* xlwt == 1.3.0
* openpyxl == 3.0.7
* 자신의 크롬 버전과 맞는 chromedriver.exe 파일이 NaverScrapper_202109.ipynb 와 같은 경로에 필요 ( 크롬 드라이버 다운로드 https://chromedriver.chromium.org/downloads )


## Usage
네이버 카페 게임 섹션에서 수집할 기간(일단위)을 입력하면 조건에 맞는 카페들의 게임 명, 카페 명, 카페 주소, 카페 멤버수, 카페 총게시물 수, 게시판 이름, 글 작성 시간, 글 내용(타이틀)을 수집하여 엑셀과 csv파일로 Log 폴더에 저장합니다.

<details><summary><b>Show instructions</b></summary>

  1. 주피터노트북에서 프로젝트를 실행
  2. 데이터를 추출할 기간 입력
  3. 데이터 추출
  4. Log 폴더에 저장

</details>


## Demo

![ezgif com-gif-maker](https://user-images.githubusercontent.com/59993977/151080112-ea91ed38-3c74-4ede-b928-31c6d556ec02.gif)
https://youtu.be/c7IDhbdhjLE

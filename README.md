## 📋 프로젝트 개요
> **프로젝트명** : 크롬앱 <br/>
**개발 기간** : 2022년 10월 1일 ~ 2022년 10월 14일 (2주)  <br/>
**분류** : 개인 프로젝트 <br/>
**역할 및 기여도** : UI/UX 디자인 및 개발 100%<br/>
**사용 기술** : `HTML`, `CSS`, `JavaScript`
<br/>
<br/>
<br/>
<br/>
<br/>

## 🔍 프로젝트 소개
노마드 코더의 ['바닐라 JS로 크롬 앱 만들기'](https://nomadcoders.co/javascript-for-beginners) 강의를 수강한 후 만든 프로젝트입니다.
강의에서 구현하는 내용 외에 기능을 추가하였고 직접 Figma를 사용해 UI를 디자인하여 진행했습니다. 강의 내용에 더해 추가한 기능들은 아래와 같습니다.
<br/>
<br/>
<br/>
<br/>
<br/>


## ✨ 결과물
#### 배포 링크
[https://angie-momentum.vercel.app/](https://angie-momentum.vercel.app/)
<br/>
<br/>
<br/>
<br/>
<br/>


## 👩🏻‍💻 기술 스택
- `HTML`, `CSS`, `JavaScript`
<br/>
<br/>
<br/>
<br/>
<br/>

## 💡 주요 기능
1. 북마크
	- 북마크 추가
   	- 북마크 삭제
    	- 북마크 수정

2. 투두리스트
	- 카테고리 태그 추가
	- 카테고리 태그 삭제
    	- 할일을 추가할 때 카테고리 태그 선택
    	- 태그가 있는 할일, 태그가 없는 할일 모두 추가 가능
    	- 카테고리가 추가된 할일은 리스트에 태그 보이기

3. 음악 플레이어 (iframe API 사용)
	- 유튜브 URL로 음악 추가
    	- 플레이리스트 상의 음악 삭제
    	- 플레이리스트 상의 음악 클릭하면 해당 음악 재생
    	- 현재 재생 중인 음악 표시
    	- 음악 재생 및 일시정지
    	- 이전 곡, 다음 곡 재생

4. 날씨
	- 4일 동안의 날씨 예보

5. 랜덤 명언
	- 새로고침 시 랜덤으로 영어 명언 표시
<br/>
<br/>
<br/>
<br/>
<br/>


## 💭 프로젝트 회고
### 나의 고민들

> 효율적이고 가독성이 높은 코드란?

변수명과 클래스명을 어떻게 하면 가독성있게 작성할 수 있을지에 대한 고민을 하기 시작했다. 내 생애 처음으로 '코드'로 이루어진 프로젝트이기 때문에 **일단 어떻게든 만들어내는 것이** 목표였다. 그래서 맨땅에 헤딩하는 기분으로 다소 주먹구구식으로 코드를 짰기 때문에 기능이 더해질수록 코드가 지저분해지는 걸 느꼈다.
<br/>

> 그래서 다음 프로젝트에선?

이러한 경험을 통해 다음 프로젝트에선 기능별로 CSS 파일을 분할하고 **BEM** 규칙에 지켜 가독성 있게 클래스명을 쓰고자 한다!
<br/>

> 기능적인 구조를 먼저 생각해보자

필요한 기능을 먼저 리스트업하고 그에 따라 코드 구조를 먼저 생각했으면 좋았을 것 같다. 음악 플레이어 구현시 다양한 경우의 수(음악 재생 중에 음악을 삭제하는 경우, 음악이 재생되는 중에 모든 음악이 삭제되는 경우 등...)를 고려해야했는데, 코드를 짤수록 다양한 변수들을 맞이하며 코드 구조가 뒤죽박죽되는 경험을 했다. 무작정 키보드를 두들기기 보다는 전체적인 구조를 먼저 고민하고 코드를 작성하면 좋을 것 같다.
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

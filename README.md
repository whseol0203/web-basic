# 목적
CSS 연습

----------------------

## 블록 레벨 요소와 인라인 레벨 요소

 #### 블록 레벨 
> 블록 요소는 혼자 한 줄을 차지하는 요소. <br>
> 너비나 마진, 패딩 등을 이용해서 크기나 위치지정을 하려면 블록 레벨 요소여야함

<br>

 #### 인라인 레벨 
> 인라인 요소는 화면에 표시되는 콘텐츠만큼만 영역을 차지하고 나머지공간에는 다른 요소가 올 수 있음. <br>
> img, strong 등이 인라인

------------------------

## display 속성

> display 속성을 사용하면 블록 레벨 요소를 인라인 레벨 요소로 바꾸거나 그 반대도 가능함.

1. display 의 속성
    * block : 블록이 된다.
    * inline : 인라인이 된다.
    * inline-block : 인라인 레벨로 배치하지만 내용에 블록 레벨 속성을 집어넣을 수 있다.
    * none : 아예 표시를 하지 않음.
    * 더 있으나, 나중에 찾아서 쓰던지 나중에 추가하겠음.

## 박스 모델 

> 웹 문서의 블록 레벨 요소들은 모두 박스 모델 형태이다.
 박스 모델은 콘텐츠 영역, 패딩, 테두리, 마진 형태로 구성된다.

1. 박스 모델의 속성
    * width : 콘텐츠 영역의 너비
    * height : 콘텐츠 영역의 높이
   
2. 패딩, 테두리, 마진
> 속성은 더 있으나, 순서를 기억할 것 (안쪽부터)

    1. 패딩
    2. 테두리
    3. 마진



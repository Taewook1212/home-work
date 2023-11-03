# home-work

멋쟁이 사자처럼 프론트엔드 스쿨 8기 : home-work
5조. 강태욱

<h1>HTML MarKup</h1>

section_container(전체박스)
section top**container
section top**left (오뚜기마크와 글 박스)
image 로고
h2 글
section top_right (꿀차이미지 담은 박스)
image 꿀차이미지
button
image 회색 처음 버튼

    section bottom__container
        section kamill  왼쪽 음료박스
          image
          h2
          image
          div
            image 클릭하면 나오는 파란색 구매버튼
            image 회색 처음 버튼
        section bori  오른쪽 음료박스
          image
          h2
          image
          div
            image 회색 처음 버튼

스크린리더로 테스트 아직 못함

<h1>CSS Markup</h1>

1. 초기화 및 기본 세팅

/_ App Colors _/

/_ Color _/

2. 윗쪽 음료 박스

   전체박스
   .container

   왼쪽 이미지와 글귀  
    .top\_\_left

   오른쪽 이미지
   .top\_\_right

   .ottogi**button,
   .bori**button,
   .kamill\_\_button
   버튼 공통 설정

   .ottogi\_\_logo
   로고

   .ottogi\_\_button
   버튼

3. 아랫쪽 음료 박스

   .bottom\_\_container
   전체박스

   .kamill
   왼쪽 kamill음료 박스
   그다음 이미지 타이틀 버튼

   .kamill\_\_button:active
   이 부분에만 클릭 버튼 효과 적용.
   (여기까지만 구현)

   .bori
   오른쪽 보리차 음료 박스
   그다음 이미지 타이틀 버튼

<h1>스크린샷</h1>

![스크린샷 2023-11-04 023339](https://github.com/Taewook1212/home-work/assets/147236247/fbf14ba9-151d-45d7-9f49-98562ff4a1df)

<h1>어려웠던 부분</h1>

피그마에 있던 사진보다 항상 조금씩 크기가 다른것같습니다.
어쩔 수 없이 1px 3px 5px 조금씩 이동시켜서 맞추는식으로 했습니다.
크게 3개로 나뉜 박스들 사이에 간격을 맞추기 어려웠습니다
각 이미지와 글이 박스 안에서 padding과 margin을 항상 햇갈렸습니다.
다음 과제는 완성된 과제로 스크린리더와 리드미 파일을 좀 더 깔끔하게 올리도록 하겠습니다.
감사합니다.

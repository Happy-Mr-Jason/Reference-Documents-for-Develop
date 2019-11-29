# Reference-Documents-for-Develop
I think this is a very useful document for beginners. It shows a lot of references to the question.


// 키보드 자동 내리기 소스

InputMethodManager imm = (InputMethodManager)getSystemService(Context.INPUT_METHOD_SERVICE);
imm.hideSoftInputFromWindow(v.getWindoToken(),0);

//Animation Gif 파일을 Animation 구현 없이 바로 보여주는 라이브러리
com.github.bumptech.glide:glide:3.7.0
https://github.com/bumptech/glide


//모든 이미지(Drawable) Animation 효과 주기
res에  anim 폴더를 추가한다.
anim 폴더에  .xml 파일로 animation을 구성한다.
Activity onCreate()에서 Animation Class로 .xml파일을 불러온다.
불러온 Animation Class의 Instance 변수를
View.sartAnimation(Animation) 또는 View.setAnimation(Animation)으로 붙여준다.
Animation 효과는 Drawable을 가진 모든 Object에 적용할 수 있다.
https://developer.android.com/guide/topics/graphics/view-animation#java

// 날짜 시간 계산 처리 관련 자료
https://jang8584.tistory.com/232

// 데이터 차트 라이브러리
com.github.PhilJay:MPAndroidChart:v3.1.0
https://github.com/PhilJay/MPAndroidChart

//SQLite Keywords
https://www.sqlite.org/keyword_index.html

//SQL Statements Learn & Test
https://www.w3schools.com/sql/default.asp

// Android Design 요소
https://material.io/
https://material.io/develop/android/components/dialog/

//기기의 외부 저장소 경로 못 찾는 이유
https://mantdu.tistory.com/685

//리소스 폴더 관리 요령
https://developer.android.com/studio/write/add-resources.html


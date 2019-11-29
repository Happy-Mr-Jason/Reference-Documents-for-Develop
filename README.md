# ■ Reference-Documents-for-Develop
I think this is a very useful document for beginners. It shows a lot of references to the question.

### ◇ Git README.md 편집하는 방법
    https://github.com/sejong-interface/Interface_Manual/wiki/Git-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0%233-README.md-%ED%8C%8C%EC%9D%BC-%EC%9E%91%EC%84%B1%ED%95%98%EA%B8%B0!

### ◇ 키보드 자동 내리기 소스
  InputMethodManager imm = (InputMethodManager)getSystemService(Context.INPUT_METHOD_SERVICE);
  imm.hideSoftInputFromWindow(v.getWindoToken(),0);

### ◇ Animation Gif 파일을 Animation 구현 없이 바로 보여주는 라이브러리
  1. com.github.bumptech.glide:glide:3.7.0
  2. https://github.com/bumptech/glide

### ◇ 모든 이미지(Drawable) Animation 효과 주기
  1. res에  anim 폴더를 추가한다.
  2. anim 폴더에  .xml 파일로 animation을 구성한다.
  3. Activity onCreate()에서 Animation Class로 .xml파일을 불러온다.
  4. 불러온 Animation Class의 Instance 변수를
  5. View.sartAnimation(Animation) 또는 View.setAnimation(Animation)으로 붙여준다.
  6. Animation 효과는 Drawable을 가진 모든 Object에 적용할 수 있다.
  7. https://developer.android.com/guide/topics/graphics/view-animation#java

### ◇ 날짜 시간 계산 처리 관련 자료
  1. https://jang8584.tistory.com/232

### ◇ 데이터 차트 라이브러리
  1. com.github.PhilJay:MPAndroidChart:v3.1.0
  2. https://github.com/PhilJay/MPAndroidChart

### ◇ SQLite Keywords
  1. https://www.sqlite.org/keyword_index.html

### ◇ SQL Statements Learn & Test
  1. https://www.w3schools.com/sql/default.asp

### ◇ Android Design 요소
  1. https://material.io/
  2. https://material.io/develop/android/components/dialog/

### ◇ 기기의 외부 저장소 경로 못 찾는 이유
  1. https://mantdu.tistory.com/685

### ◇ 리소스 폴더 관리 요령
  1. https://developer.android.com/studio/write/add-resources.html


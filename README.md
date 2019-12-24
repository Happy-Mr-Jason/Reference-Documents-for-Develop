# ■ 초보 안드로이드 개발용 참조문서
# ■ Reference-Documents-for-Beginner
I think this is a very useful document for beginners. It shows a lot of references to the question.

### ◇ Android Studio installation & Config
   https://developer.android.com/studio/intro
   
### ◇ GitHub Help 
   https://help.github.com/en/github
    
### ◇ 키보드 자동 내리기 소스
```java
  InputMethodManager imm = (InputMethodManager)getSystemService(Context.INPUT_METHOD_SERVICE);
  imm.hideSoftInputFromWindow(v.getWindoToken(),0);
```
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
  
### ◇ Navigation Drawer 사용하기 (주의! Deprecated : 더이상 사용안함)
  1. Developers-Document-Guide
     https://developer.android.com/guide/navigation/navigation-ui#add_a_navigation_drawer
  2. 참조 블로그
     https://webnautes.tistory.com/1017
  3. MainActivity용 xml파일의 Layout을 androidx.drawerlayout.widget.DrawerLayout 으로 지정한다.
     https://developer.android.com/jetpack/androidx/releases/drawerlayout
  4. DrawerLayout내에 com.google.android.material.navigation.NavigationView 을 포함시킨다.
     https://developer.android.com/reference/android/support/design/widget/NavigationView
  5. ActionBar에 home 버튼을 추가해서 home 버튼 아이콘 변경 및  onOptionsItemSelected Listener에 NavigationView를 opneDrawer로 열어준다.
  6. NavigationView의 내용은 menu/.xml로 만들어서 menu속성에 연결시켜준다.
  7. 만들어둔 예제 파일
     https://github.com/Happy-Mr-Jason/NavigationDrawerEx

### ◇ Android Socket통신시 문제점 발견 (통신등의 시간이 많이 걸리는 작업을 수행 하는 경우)
  1. 통신 등의 시간이 많이 걸리는작업(수행 중 대기 하는 경우 또는 수행에 오래걸리는 매서드를 실행 할 경우)을 실행 할 경우
     MainThread에서 에러가 발생하거나. 실행이 지연되어 앱의 응답성을 떨어뜨리는 경우가 발생하므로 적절한 조치가 필요하다.
  2. 따라서 이런 경우 UIThread 보다는 별도의 Background급의 WorkerTrhead를 만들어서 수행해야 응답성이 좋아지게 된다.
  1. NetworkOnMainThreadException
     https://developer.android.com/reference/android/os/NetworkOnMainThreadException
  2. NetworkOnMainThreadException 해결 방안
     https://developer.android.com/training/articles/perf-anr#java
     
### ◇ Android Studio 가 백신프로그램의 실시간 검사 사용시 느려지는 현상과 조치 방법
  1. https://developer.android.com/studio/intro/studio-config#antivirus-impact
  
### ◇ ViewPager2 API Document offscreenPageLimit
  1. https://developer.android.com/reference/androidx/viewpager2/widget/ViewPager2#setOffscreenPageLimit(int)
  
### ◇ Make a Class from Json
  1. http://www.jsonschema2pojo.org/

# Simple-Web-Browser
### 웹 브라우저의 간단한 기능을 구현한 안드로이드 앱

#### 도메인 주소를 검색하고 웹 서핑을 지원하는 간단한 웹 브라우저 기능을 구현한 앱 입니다.
### Blog
* <https://hwayomingdlog.tistory.com/227>
</br>


## 주 기능
### 검색 Search
* 네비게이션 바의 검색창을 통해 서핑하고자 하는 웹 사이트 주소를 검색할 수 있습니다.

### 뒤로가기 Go Back
* 네비게이션 바의 ⬅️ 버튼을 클릭해서 이전 탐색으로 돌아갈 수 있습니다.

### 앞으로가기 Go Forward
* 네비게이션 바의 ➡️ 버튼을 클릭해서 이후에 탐색한 페이지로 갈 수 있습니다.

### 홈 Home
* 네비게이션 바의 🏠 버튼을 클릭해서 홈 화면인 구글 검색창으로 갈 수 있습니다.

### 새로고침 Refresh
* 웹 페이지의 상단에서 하단으로 스와이프를 하면 페이지가 새로 고침 됩니다.
</br>


## 활용 기술
* WebView - WebView를 사용해서 웹 페이지를 앱에 띄우고, WebView의 goBack(), goForward(), reload() 메서드를 활용해서 뒤로가기, 앞으로가기, 새로고침 기능을 구현했습니다.
* ContentLoadingProgressBar - WebView에서 페이지 로드가 시작될 때부터 완료될 때까지의 진행 상태를 보여주는 게이지 바를 네비게이션 바 아래에 적용했습니다.
* WebViewClient - WebViewClient의 onPageStarted(), onPageFinished() 메서드를 오버라이딩하여 WebView에서 페이지 로드를 시작할 때, 완료되었을 때 필요한 UI 작업을 적용하였습니다.
* SwipeRefreshLayout - WebView의 상단에서 하단으로 스와이프를 하였을 때, 새로고침을 적용하기 위해 SwipeRefreshLayout을 적용했습니다.
</br>

***
<img src="/img/img0.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img1.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img2.png" width="300px" height="600px" title="" alt=""></img>

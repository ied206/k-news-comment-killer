# Joveler's K-News Comment Killer
K-News Comment Killer는 대한민국 뉴스 서비스의 댓글들을 차단하는 uBlock Origin 및 AdBlock Plus용 필터입니다.

눈살을 찡그리게 만드는 뉴스 댓글을 치워버리세요!

이 [주소](https://raw.githubusercontent.com/ied206/k-news-comment-killer/master/comments.txt)를 복사해 uBlock Origin 및 AdBlock Plus에 추가하세요.

PC뿐만 아니라 모바일에서도 사용 가능합니다!  
자세한 설치법은 밑에서 찾을 수 있습니다.

# 설치
## uBlock Origin
1. uBlock Origin의 대시보드에 들어갑니다.  
> Firefox : `부가 기능 - 확장 기능 - uBlock Origin - 설정 - 대쉬보드 보기`  
> Chrome : `설정 - 확장 프로그램 - uBlock Origin - 옵션`  
2. 대시보드의 `보조 필터` 탭을 선택합니다.
3. 아랫쪽에서 URL을 입력하는 칸을 찾습니다.  
> `한 줄에 한 개의 URL을 입력하세요.`라는 문장 밑의 입력칸입니다.
4. 다음 URL을 입력합니다.   
> https://raw.githubusercontent.com/ied206/k-news-comment-killer/master/comments.txt
5. '분석' 버튼을 누릅니다.
6. 오른쪽 위의 '변경사항 적용' 버튼을 누르십시오.
7. 성공적으로 적용되었습니다.

## AdBlock Plus
1. AdBlock Plus의 필터 설정 창에 들어갑니다.  
> Firefox : `부가 기능 - 확장 기능 - AdBlock Plus - 필터 설정`  
> Chrome : `설정 - 확장 프로그램 - AdBlock Plus - 옵션`  
2. `구독 필터 추가` 버튼을 누른 뒤 `다른 구독 필터 추가`를 누르십시오.
3. 다음 정보를 입력합니다.  
> 이름 : Joveler's K-News Comment Killer  
> 위치 : https://raw.githubusercontent.com/ied206/k-news-comment-killer/master/comments.txt
4. 성공적으로 적용되었습니다.

## Android
1. 부가기능을 지원하는 [Android용 Firefox](https://play.google.com/store/apps/details?id=org.mozilla.firefox)를 설치합니다.
2. AdBlock Plus와 호환되는 차단용 부가 기능을 설치합니다.  
   성능이 가장 좋은 uBlock Origin을 추천합니다.  
   [모질라 부가 기능 홈페이지](https://addons.mozilla.org/ko/android/addon/ublock-origin)에서 설치할 수 있습니다.  
3. uBlock Origin의 대시보드에 들어갑니다.  
> 진입 방법 : `메뉴 - 도구 - 부가 기능 - uBlock Origin - 대쉬보드 보기`
4. 이후는 PC와 동일합니다.

# 정책
대한민국 포털이 기사를 송고받는 언론사 및 저명성이 있는 매체의 **자동으로 표시되는** 댓글을 차단하는 것을 목표로 하고 있습니다.  
댓글이 가려져 있는 경우, 스크롤을 내리는 것만으로는 화면에 표시되지 않기 때문에 리스트에 추가하지 않습니다.  

현재 지원하는 언론사들의 명단은 [list.csv](https://github.com/ied206/k-news-comment-killer/blob/master/list.csv)에서 확인하실 수 있습니다.  

언론사 홈페이지가 개편되는 경우, DOM 구조가 변해 댓글이 제대로 차단되지 않을 수 있습니다.  
또한, 아직 추가되지 않은 언론사 홈페이지가 있을 수 있습니다.  
이 경우, 저에게 Issue나 Pull Request를 통해 알려주시면 시간이 나는 대로 반영하겠습니다.  


# 관련 문의
언론사 추가 등 건의사항이 있다면, Issue나 Pull Request로 알려 주시기 바랍니다.

#Mark Down
Mark down 이라는 툴을 아주 쉽게 배워 보도록 하겠습니다.

먼저 설치 과정입니다. **설치 과정**은 일단 아래 주소에 따라 진행해 주세요

http://www.hallym.ac.kr

[링크 사이트](http://www.hallym.ac.kr "허버링 글씨도 작성가능하네요")

* 결과는 다음과 같습니다.
* 두번째도 마찬가지 입니다.
	* 리스트 하위도 이렇게 간단하게 만드네됴
	* 헐!
		* 뭐야 보여주기 위한 코드로는 이만한게 없쟈너.
		 

#리스트
1. 이렇게 하면
2. 리스틀 좀더 다양하게
3. 앞에 리스번호는 에디터에서 자동으로 만들어 주니 편하죠

-------

>인용을 한번 해보도록 하죠. 아주 쉽게 진행할 수 있습니다. 개행을 해도 인용이 그대로 적용된다고 하니 더 편하겠죠


```   
#include "stdio.h"

int main(int argc, char const *argv[])
{
	/* code */
	return 0;
}
```

위와 같이 코드 `printf` 함수를 작성하고 실행을 해봅니다.

결과는다음 과 같습니다.

	Hello World
	C:\GitHub\Tutorial\lec_Html5\Test>

##수식 작업
제목2는 자동으로 줄이 하나생기네요

수식도 한번 작업해볼까요?

\\({e}^{i\pi}+1=0\\)

<p>$ x $에 관한 이차방정식 $ ax^2 + bx + c = 0 $의 해는 다음과 같다.</p>
<p>$$ x = \frac{-b \pm \sqrt{b^2-4ac}}{2a} $$</p>



##이미지작업
###기본코드

###로컬이미지

![](Img1120097.png)

이게 C: 부터 경로를 읽을 수 없고 본인이 있는 폴더를 기준으로 움직이네요


###이미지의 크기를 줄이자
md 에는 이미지크기를 줄이는 기능이 없네 외부의 도움이 필요할듯

<img src="img/Img1120097.png" width="200">

그냥 html 코드를 바로 삽입하는 방법

CSS 파일의 도움을 받는 방법

서비스 (github 나 다른 모듈) 의 도움을 받는 방법 등이 있을 수 있다.

###다른 페이지 이동

[test3](test3.md)


###테이블

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell


| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display~~ the help window.|
| Close     | Closes a window|

정렬도 가능하지요

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
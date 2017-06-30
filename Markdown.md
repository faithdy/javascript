<!-- 문단 제목 -->

# 1단계 제목
이것은 1단계 제목입니다.

## 2단계 제목
이것은 2단계 제목입니다.

# 목록
순서가 없는 목록
* 목록 하나
* 목록 둘
- 목록 셋

순서가 있는 목록
1. 목록 첫째
2. 목록 둘째
4. 목록 셋째
    1. 소목록
    2. 이것도 소목록
        - 그렇다.
    3. 소목록이에용

# 글자 모양
**굵게** 쓰려면 'b'old text  
*기울게* 쓰려면 'i'talic text  
~~취소~~는 물결 두개로.  
강제 개행은 줄 끝에 공백 두칸  

# 코드
'code'를 이용합니다.
```
#include <stdio.h>
int main(void) {
  return 0;
}
```
`printf("Hello");`

Syntax Highlight  
code 우측에 'clike', 'ruby'등을 설정.
```c++
#include <stdio.h>
using namespace std;
int main(void) {
  return 0;
}
class Node {
  private:
    int number;
    class *pNext;
  public:
    int getNumber();
    int getpNext();
}
```

# 인용문
꺽쇠>를 이용합니다.
> 안녕  
> 이것은 인용문.

# 링크
링크는 'l'을 이용.

[네이버 링크](http://www.naver.com)

[깃허브 내 연관링크](README.md)

# 그림 넣기
이미지는 'img'를 이용.
![꽃](http://thumb.photo.naver.net/exphoto02/2011/2/23/111/%B9%D9%B6%F7%B0%B3%BA%F1_016_ghxhghtns.jpg "툴팁 메시지. 이 부분은 생략해도 됩니다.")

# 가로줄
* * *
***
*****

# 태스크
't'를 눌러서 todo 활성화 합니다.
- [x] 마크다운 언어 학습하기.
- [ ] java script 언어 공부하기.

# 테이블
'table'을 이용해서 활성화 합니다.

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

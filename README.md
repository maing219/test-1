# 자주 사용하는 마크다운 문법

# 제목
# test
## test
### test
#### test
##### test
###### test

# 가로줄
---
----
***
*****
* * *

# 순서있는 목록
1. 원격 저장소 만들기
2. origin 연결하기
3. psuh
4. pull vs fetch
5. 협업하기

# 순서 없는 목록(+, -, * 를 붙여서 나열, 구별없이 사용 가능)
- 원격 저장소 만들기
  - origin 연결하기
  - push
+ pull vs fetch
  * pull
  * fetch
-  협업하기

# 텍스트 강조
- 굵게 (**)
- 기울임체 (*)
- 굵은 기울임체 (***)
- 취소선 (~~ )

**GitHub**는 원격 저장소를 제공하 ~~는 서비스_~~ 기 때문에 따로 Git을 *설치*하지 않고도 온라인 상에서 Git의 ***버전 관리 기능***을 사용할 수 있습니다.

# 인용
- &gt; : 인용문
- &gt;&gt; : 인용문 안에 인용문

> The information manager from hell.
>> git means "global infromation tracker"

# 소스코드(backtic)
- 한줄짜리 소스코드는 `function add(x, y){return x}`
- 여러줄의 소스코드
```
<script>
var today = new Date();
document.write(today);
</script>
```

# 링크
1. <링크주소>
2. [링크텍스트](링크주소)
3. [링크텍스트](링크주소, "부가 설명") : 링크 텍스트 위로 커서를 올리면 부가설명이 말풍선으로 나옴

- <http://www.google.com>
- [구글](http://www.google.com)
- [구글](http://www.google.com, "검색 사이트")

# 이미지
- 이미지 들어있는 디렉터리를 원격 저장소로 드래그 후 코드 넣기
- 파일탐색기에서 이미지를 직접 드래그
- ![이미지텍스트](./이미지 경로)

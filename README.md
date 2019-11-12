# AndroidPrograming_Lesson

### git 명령어
>1.현재 git의 버전을 확인
   - git --version

>2.수정되지 않은 변경사항을 조회하기
 - git status

>3.원본 영역과 수정된 영역 사이의 차이점 알아보기
 - git diff

>4.git 명령어전역 설정 정보 조회
 - git config --global --list

>5.전역 설정 정보 삭제시키기
 - git config --global --unset-all user.email

>6.새로운 저장소 초기화하기
 - git init

>7.아직 수정 완료를 하지 않은 파일의 변경내용을 취소하고 이전 상태로 돌립니다
 - git checkout -- 파일명

>8.저장소 복제하기
 - git clone <저장소 url>

>9.새로운 원격 저장소 추가하기
 - git remote add <원격 저장소> <저장소 url>

>10.새로운 파일 git에 등록시키기
 - (staging)git add <파일>
 
>11.현재까지 작업한 내용 저장하기
 - git commit -m “<메시지>”

>12.원격 저장소에서 합치지 않고 지역 브랜치로 변경 사항 가져오기
 - git fetch <원격 저장소>

>13.원격 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기
 - git pull <원격 저장소>

>14.새로운 로컬 브랜치를 원격 저장소에 푸싱하기
 - git push <원격 저장소> <지역 브랜치>

>15.다른 브랜치를 현재 브랜치로 합치기
 - git merge <브랜치>

>16.모든 이력 보기
 - git log
 
>17.20개의 항목과 패치만 보이도록 로그 제한하기
 - git log -20 -p

>18.이틀 전까지의 커밋 로그 보기
 - git log --before=”2 days”

>19.파일의 커밋 정보 줄 단위로 보기
 - git blame <파일>

>20.각 항목의 로그 이력 한 줄씩 보기
 - git log --pretty=oneline


### Markdown 명령어
>1.헤더
- `# 대주제`
- `## 중주제`
- `### 소주제`
# 대주제
## 중주제
### 소주제 

>2.글자 기본 포맷
- `**Bold**`
- `__Bold__`
- `*Italic*`
- `_Italic_`
- `~~Cancel~~`

**Bold**
__Bold__
*Italic*
_Italic_
~~Cancel~~

>3.링크 넣기
- `[name](주소)`

>4.원하는 색상 넣기
- 기본적으로 문법에서 지원하지는 않는다.
- HTML 태그를 사용해야한다.
- `<span style="color:red">내용</span>`

>5.인용구 이용
- `>인용구`

>6.구분선 삽입
- `-------`
------

>7.하이퍼링크 첨부
- `[텍스트 이름](링크)`

>8.이미지 삽입
- `![이미지 이름](링크)`

>9.리스트
-  `* 내용1`<br>
   `* 내용2`<br>
     `* 하위내용1`<br>
     `* 하위내용2`
 
   * 내용1
   * 내용2
     * 하위내용1
     * 하위내용2



# Markdown 문법

### 인라인 코드블럭& 줄바꿈
> `<br>inline code`
<br>`inline code`

### 문자열
> `*기울이기*` <br>
> `"**진한 문자열**` <br>
> `~~취소선~~` <br>
> `<u>밑줄</u>`

*기울이기*<br>
**진한 문자열**<br>
~~취소선~~<br>
<u>밑줄</u>

### 리스트
> `* 리스트1`<br>
> `* 리스트2`<br>
> `  * 리스트2-1`<br>
> `    * 리스트2-1-1`<br>
> `* 리스트3`

* 리스트1
* 리스트2
  * 리스트2-1
    * 리스트2-1-1
* 리스트3

### 숫자 리스트
> `1. 숫자 리스트1`<br>
> `2. 숫자 리스트2`

1. 숫자 리스트1
2. 숫자 리스트2


### 이미지
> `![Markdown Here logo](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon24.png)`
> `[링크](http://sonim1.tistory.com)`

![Markdown Here logo](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon24.png) 
[링크](http://sonim1.tistory.com)

### 인용문
> 인용문. 
>>중첩
>>>중중첩1<br>
>>>중중첩2
 
### 헤더
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

### 구분선
---

### 테이블
> `| 한글 | 숫자 | 영어 |`<br>
> `| ------------- |:-------------:| -----:|`<br>
> `| ㅁㄴㅇ | 77 | aa|`<br>
> `| ㅁ | 88 | bb |`<br>
> `| ㄴ | 99 | cc |`<br>

| 한글 | 숫자 | 영어 |
| ------------- |:-------------:| -----:|
| ㅁㄴㅇ | 77 | aa|
| ㅁ | 88 | bb |
| ㄴ | 99 | cc |

### url링크
> `[ㅁㅁ]: https://naver.com`<br>
> `[NAVER](https://naver.com "네이버.")`<br>
> `[첫번째][1]`<br>

[ㅁㅁ]: https://naver.com <br>
[NAVER](https://naver.com "네이버.")<br>
[첫번째][1]<br>


# git 명령어


### 전역 설정 정보 조회
>  git config - -global - -list

### 전역 설정 정보 삭제시키기
> git config --global --unset-all user.email

> git config --global --unset-all user.name




### 새로운 저장소 초기화하기
> git init

### 저장소 복제하기
>  git clone <저장소 url>

### 새로운 원격 저장소 추가하기
>  git remote add <원격 저장소> <저장소 url>

### 새로운 파일 git에 등록시키기(staging)
> git add <파일>

### 현재까지 작업한 내용 저장하기

> git commit -m “<메시지>”


### 원격 저장소에서 합치지 않고 지역 브랜치로 변경 사항 가져오기
> git fetch <원격 저장소>

### 원격 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기
> git pull <원격 저장소>

### 새로운 로컬 브랜치를 원격 저장소에 푸싱하기
> git push <원격 저장소> <지역 브랜치>

### 변경된 코드의 상태를 확인할 수 있는 명령어
> git status

### git add를 통해 업데이트할 브랜치가 마스터인지 아니면 사용자들이 만들어 놓은 브랜치 인지를 알려준다
> git branch

### 팀원들이 만든 브랜치나 내가 만든 브랜치, 또는 마스터 등올 브랜치를 스위칭할수 있다.
> git checkout

### 지금까지의 변경 내용을 전부 해당 브랜치에 병합
> git merge

### 가장 최근에 커밋했던 내용을 불러온
> git reset --hard

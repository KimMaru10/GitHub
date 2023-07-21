# 깃허브 튜토리얼

## 저장소 생성하기 
깃허브 리드미를 사용하려면 먼저 저장소 생성을 해야된다. 
1. 화면 오른쪽 위 코너에 +버튼을 누르고 New repository버튼을 누릅니다. 
<img width="1680" alt="스크린샷 2023-07-05 오후 1 28 10" src="https://github.com/KimMaru10/GitHub/assets/131854855/8791516d-4f1d-40cf-aa02-5e37b5e7cd81">
2. 저장소 이름을 적습니다.(필수)<br>
3. 저장소에 대한 짧은 설명을 적습니다.<br>
4. add a Redme file을 체크 해줍니다. <br>
5. Create repository를 클릭하여 저장합니다.
<img width="1680" alt="스크린샷 2023-07-05 오후 1 27 46" src="https://github.com/KimMaru10/GitHub/assets/131854855/9f91ff83-ec21-430c-9ef4-489ee997809c">

## 리드미 내용 작성하기
내용은 Edit file에 작성을 합니다. 
<img width="1680" alt="스크린샷 2023-07-05 오후 2 56 32" src="https://github.com/KimMaru10/GitHub/assets/131854855/1f380c9a-7886-471f-beaa-cec2a2bf94f7"><br>

### Usage 1. 글머리 작성방법
글머리는 # 을 이용해서 작성합니다. <br>
<hr>
-결과물<br>
<img width="500" alt="스크린샷 2023-07-05 오후 3 24 43" src="https://github.com/KimMaru10/GitHub/assets/131854855/c6d8372e-35c5-49f9-8ee6-4ee61703a3c5">

###  Usage 2. 코드블럭 작성방법 
코드를 작성하기 위해서는 아래와 같이 `을 사용하고 그 뒤에 사용하는 언어를 작성하시면 됩니다. <br>
<img width="152" alt="스크린샷 2023-07-05 오후 3 16 56" src="https://github.com/KimMaru10/GitHub/assets/131854855/fbb37377-1fe9-4ed9-81b2-704ef7810372"><br>
다음와 같이 작성하면 아래와 같은 결과를 출력할 수 있습니다. 
<hr>
-결과물<br>


```HTML
<h2> Hello </h2>

```

### Usage 3. 링크 작성 방법
아래와 같이 [블로그명]와(URL링크)로 작성하면 됩니다.<br>
<img width="291" alt="스크린샷 2023-07-05 오후 3 25 42" src="https://github.com/KimMaru10/GitHub/assets/131854855/791055e6-9040-4f59-85f0-e620fcd06920"><br>
<hr>
-결과물<br> 
[블로그명](https://github.com/KimMaru10/)<br>
이때 []와()사이에 공백이 들어가면 링크 작성이 제대로 이루어 지지 않습니다.

### Usage 4. 순서 있는 리스트
아래와 같이 한가지 숫자로 나열해도 좋고 순서대로 1,2,3와 같이 작성 해도 같은 결과를 볼 수 있다. 
<img width="108" alt="스크린샷 2023-07-05 오후 3 40 20" src="https://github.com/KimMaru10/GitHub/assets/131854855/4670ed5a-6dbe-49aa-b509-892fa877c86e"><br>

<hr>
-결과물<br>
1. 순서 있음
1. 순서 있음
1. 순서 있음

### Usage 5. 순서 없는 리스트
글머리 기호 *, -, + 지원<br>
* 순서 없음
  * 순서 없음
    * 순서 없음

- 순서 없음
  - 순서 없음
    - 순서 없음

+ 순서 없음
  + 순서 없음
    + 순서 없음
<br>

### Usage 6. 수평선
방법1. <br>
<img width="68" alt="스크린샷 2023-07-05 오후 3 52 50" src="https://github.com/KimMaru10/GitHub/assets/131854855/d3bba7ac-9cac-41d0-ae6f-b61df81f352f"><br>
방법2.<br>
<img width="60" alt="스크린샷 2023-07-05 오후 3 52 54" src="https://github.com/KimMaru10/GitHub/assets/131854855/92848072-403c-44af-80e1-90d01f678281">

-결과물
<hr>

### Usage 7. 강조 

<img width="221" alt="스크린샷 2023-07-05 오후 3 59 42" src="https://github.com/KimMaru10/GitHub/assets/131854855/5bf62c05-7810-4a84-8aad-a3a4ee88d272">
<br>
<hr>
-결과물
*강조하기*
_강조하기_
**강조하기**
__강조하기__
~~강조하기~~

### Usage 8. 줄바꿈
방법1. \<br>태그를 줄바꿈 하고 싶은 위치에 사용<br>
방법2. 공백문자를 두번 문장 끝에 두번 사용<br>

### Usage 9. 마크다운 용법 그대로 출력
 \ 와 그대로 출력 하고 싶은 태그나 문자를 작성<br>
<img width="70" alt="스크린샷 2023-07-05 오후 4 11 22" src="https://github.com/KimMaru10/GitHub/assets/131854855/1172c4ce-eaf3-4b2c-bb0c-6293290ea009"><br>

<hr>
-결과물<br>

 \<br>

## VsCode와 Git연동 하기 
### Step1 
VsCode를 실행 시키고 VsCode에서 github 로그인을 해준다. 
<img width="1680" alt="스크린샷 2023-07-21 오후 4 50 32" src="https://github.com/KimMaru10/GitHub/assets/131854855/50919688-67bd-4b52-b003-35b8964755b0"><br>

### Step2
연동 할 프로젝트 파일 생성 한다. 
상단 폴더에서 폴더 열기를 클릭하여 생성한 파일을 열어준다. 
<img width="1680" alt="스크린샷 2023-07-21 오후 4 50 32" src="https://github.com/KimMaru10/GitHub/assets/131854855/80b0d8d8-0998-4821-8fad-47007a4fe90f"><br>

### Step3
예시 test.html파일을 만들어준다. 
<img width="1129" alt="스크린샷 2023-07-21 오후 4 52 08" src="https://github.com/KimMaru10/GitHub/assets/131854855/9914f784-88f6-44b4-accf-40cd384567bd"><br>


### Step4
왼쪽 메뉴에 소스 제어에 들어간다. 
<img width="1680" alt="스크린샷 2023-07-21 오후 4 50 39" src="https://github.com/KimMaru10/GitHub/assets/131854855/6666bbb9-3a10-484a-b3e6-915fac182578"><br>


### Step5
소스제어에 들어가면 GitHub게시 버튼을 클릭한다. 
이 버튼을 누르면 연동된 깃허브에 새롭게 래포지토리를 만들 수 있게 된다.
<img width="643" alt="스크린샷 2023-07-21 오후 4 50 53" src="https://github.com/KimMaru10/GitHub/assets/131854855/fa05a670-e15b-4c4d-96f8-a07c85d0843d"><br>

### Step6
F1를 누르고 git clone이라고 검색을 해준다. 
<img width="593" alt="스크린샷 2023-07-21 오후 4 52 14" src="https://github.com/KimMaru10/GitHub/assets/131854855/1113269d-9366-440a-b16b-f906557a7bfc"><br>

검색한 것을 클릭하게 되면 연동된 github 계정에 리포지토리를 public 아니면 private 어떤 것으로 생성할 것 인지 고르면 된다. 
나는 여기서 public을 선택했다. 
<img width="593" alt="스크린샷 2023-07-21 오후 4 52 14" src="https://github.com/KimMaru10/GitHub/assets/131854855/17fe3961-687d-4fe4-85c6-fc62ef24a015"><br>

### Step7 
클릭을 하게되면 깃허브에 리포지토리가 생성이 되고 파일이 push된 것을 볼 수 있다. 

<img width="455" alt="스크린샷 2023-07-21 오후 4 52 33" src="https://github.com/KimMaru10/GitHub/assets/131854855/df5e4f6c-c93d-41b5-90a1-470681df14f3"><br>
<img width="958" alt="스크린샷 2023-07-21 오후 4 52 41" src="https://github.com/KimMaru10/GitHub/assets/131854855/ff0b957a-cc3d-4c62-8d4a-750a17fb502d"><br>

### Step8
이제 커밋을 하는 방법을 알아 볼 것이다. 
변경 사항이 있어야 커밋을 할 수 있다. 기존 파일에 변경 사항이 없으므로 아무거나 추가해준다. 
<img width="1171" alt="스크린샷 2023-07-21 오후 4 53 16" src="https://github.com/KimMaru10/GitHub/assets/131854855/7b57d185-4d39-4d55-a7d8-3f18c9528a99">

### Step9
소스 제어에 들어가게 되면 커밋이 있다. 
이때 변경 사항에 있는 + 를 클릭을 한다. 이러면 스테이징된 변경 사항이라고 표시가 바뀐다. 
<img width="362" alt="스크린샷 2023-07-21 오후 4 53 26" src="https://github.com/KimMaru10/GitHub/assets/131854855/40a788ae-3e6e-46e5-8e24-212e6bec696c"><br>

!!여기 중요한 것이 메시지다 커밋을 할때 메시지를 입력 해주지 않으면 커밋 되지 않고 무한으로 로딩되게 된다. 
그렇기 때문에 꼭 커밋을 누르기 전에 메시지를 입력 해줘야 한다. 
<img width="284" alt="스크린샷 2023-07-21 오후 4 53 49" src="https://github.com/KimMaru10/GitHub/assets/131854855/0e56b612-74ff-4e0d-a508-dd4288af39b2"><br>

<img width="280" alt="스크린샷 2023-07-21 오후 4 54 00" src="https://github.com/KimMaru10/GitHub/assets/131854855/9c639c1b-5d63-47fe-bc06-5e32046baa84"><br>

### Step10
이제 커밋을 했으면 push를 해줘야 한다. 
변경 내용 동기화를 누르면 push가 된다. 
<img width="290" alt="스크린샷 2023-07-21 오후 4 54 07" src="https://github.com/KimMaru10/GitHub/assets/131854855/759aaf7e-867c-47ef-8ff4-1923ca87cc1f"><br>

방금 전 생성한 리포지토리에 파일이 추가 된것을 확인 할 수 있다. 
<img width="901" alt="스크린샷 2023-07-21 오후 4 54 28" src="https://github.com/KimMaru10/GitHub/assets/131854855/7c7265c1-10f4-4ad9-bdcf-57a44013455b">









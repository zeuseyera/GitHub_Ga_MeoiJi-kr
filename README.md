:kr: 깃허브란?
> 공개자료를 저장하는 **공개적인 저장소** 이며, 수정 이력을 아주 쉽게 관리한다.  
> 물론 깃허브에서 정한 비용을 지불하면 **자신만의 비공개 저장소** 를 가질 수 있다.

출처:
- https://guides.github.com/activities/hello-world/

---
*안녕 신세계(The Hello World)* 과제는 컴퓨터프로그래밍의 오랜 전통이다. 이것은 새로운 것을 배울때 처음하는 간단한 몸풀기다. 자 이제 깃허브로 출발!

무엇을 배우는가:
- 저장소 생성 및 사용
- 새 가지의 시작과 관리
- 파일을 변경하고 지르기(commit)로 밀어넣는다
- 요청끌어오기(pull request)를 열고 합치기
---

# 깃허브란 무엇인가?
깃허브는 판 조절과 협업을 위한 코드의 주인장 작업대이다. 이것은 당신과 다른사람이 어디에서나 과제를 함께 할 수 있게 한다.  

이 가르침은 저장소(repositories), 가지(branches), 지르기(commits), 그리고 요청끌어오기(Pull Request) 같은 깃허브의 필수사항을 가르친다.  

### 코딩이 필요없다

이 가르침을 완료하기 위해서는, [**GitHub.com의 계정**](http://github.com/) 과 인터넷접근이 필요하다. 코드의 작성방법은 알 필요가 없다, 명령행을 사용한다, 또는 Git(판조절 깃허브 소프트웨어는 내장(제공)됨)을 설치한다.  

> 조언: 분리된 창(또는 탭)에 이 길잡이를 연다 그러면 가르침의 단계를 완료하는 동안 볼수 있다.
---

## 단계 1. 저장소 생성

**저장소(repository)는** 하나의 과제를 구성하기 위하여 일반적으로 사용한다. 저장소는 폴더와 파일, 이미지, 비디오, 스프레드쉬트, 그리고 자료집합을 포함할 수 있다-과제에 필요한 모든것. 우리는 _README(나를봐)_ 를 포함하는것을 권고한다, 또는 과제에 대한 정보가 포함된 파일. 깃허브는 쉽게 새로운 저장소를 동시에 추가할 수 있다. _또한 권리(license)파일 같은 다른 공통 선택사양도 제공한다._

자신의 _**hello-world**_ 저장소는 아이디어, 자원을 저장, 더불어서 심지어 다른사람과 공유하고 의논하는 장소가 될 수 있다.

### 새로운 저장소를 생성하기 위하여

<p align="center"><img width="90%" src="images/저장소 생성.png" /></p>

1. 상단우측 모서리에, 자신의 아바타 또는 신원상징 옆의, **+** 를 클릭하고 **New repository(새 저장소)** 를 선택한다.
2. **Repository name(저장소 이름)** 을 _**hello-world**_ 로 한다.(2018년 01월 24일 현재 한글로된 저장소 이름은 지원이 안된다)
3. **Description(묘사)** 에 짧게 묘사한다.
4. **Initialize this repository with a README(README를 포함하여 이 저장소를 초기화)** 를 선택한다.

**Create repository(저장소 생성)** 를 누른다. :tada:

## 단계 2. 가지 생성

**가지뻗기(Branching)** 는 저장소의 다양한 판(version)을 한번에 작업하는 방법이다.

기본적으로 저장소는 _**줄기(master)**_ 라는 이름인 하나의 가지(branch)가 있다 이것은 확정된가지로 인정한다. 우리는 실험과 편집하기를 위하여 가지를 사용한다 _**줄기(master)**_ 로 지르기(커밋, commit)를 하기 전에.

_**줄기(master)**_ 에서 가지를 생성할 때, 그 시점의 _**줄기(master)**_ 로 자신의 복사본, 또는 스냅샷(snapshot)을 만든다. 만약 자신의 가지에서 작업하는 동안 다른 누군가가 _**줄기(master)**_ 를 변경했다면, 갱신된 것들을 자신의 가지에 끌어오기(pull)를 할 수 있다.

이 도형이 보여주는 것:
- _**줄기(master)**_ 라는 가지
- _**특징(feature)**_ 라고 하는 새가지(이 가지에서 '특징 작업'을 하기 때문이다)
- _**특징(feature)**_ 을 가지는 여정, _**줄기(master)**_ 로 합치기(merge) 전에

<p align="center"><img width="90%" src="images/저장소 가지.png" /></p>

다른판의 파일을 저장한 적이 있는가? 이런것 처럼:
- _**story.txt**_
- _**story-joe-edit.txt**_
- _**story-joe-edit-reviewed.txt**_

가지(branch)는 깃허브 저장소에서 비슷한 목적을 달성한다.

여기 깃허브에서, 우리 개발자, 저자, 그리고 설계자는 버그 수정을 위하여 가지(branch)를 사용한다 그리고 _**줄기(master)**_ (라고 생성된) 가지와 분리된 특징 작업을 한다. 변경사항이 준비되면, 그 가지(branch)를 _**줄기(master)**_ 로 합치기(merge)한다.

### 새가지 생성을 위하여
<p align="center"><img width="60%" src="images/나를봐-수정(readme-edits).gif" /></p>

1. _**hello-world**_ 라는 자신의 새저장소로 이동한다.
2. 파일목록의 상단에 있는 **branch:master** 라는 떨굼(드롭다운)을 클릭한다.  
3. 가지이름을 타자한다, _**readme-edits**_, 문자상자에 새가지로.
4. **Create branch** 라는 청색 상자를 클릭한다 아니면 자신의 키보드에서 “줄바꿈(Enter)”키를 누른다.

이제 2개의 가지를 가진다, _**줄기(master)**_ 와 _**readme-edits**_. 그것은 똑같아 보인다, 하지만 오래가지 않는다! 새가지에 우리의 변경사항을 추가한 다음에는.

## 단계 3. 변경하고 지르기(commit)하기

브라보! 이제, 당신은 자신의 _**readme-edits**_ 라는 가지에 대한 코드보기에 있다, 이것은 _**줄기(master)**_ 의 사본이다. 몇가지 사항을 수정해 보자.

깃허브 에서는, 저장된 변경사항을 지르기(commit)라고 한다. 모든 지르기는 연관된 지르기(commit) 알림 가지고 있다, 이것은 특별한 변경이 이루어진 이유를 설명하는 묘사이다. 지르기(commit) 알림은 자신의 변경이력을 채집한다, 그래서 자신이 한 일과 이유를 다른 참여자가 이해할 수 있다.

### 변경하고 지르기(commit)하기
<p align="center"><img width="90%" src="images/지르기(commit).png" /></p>

1. _**README.md**_ 파일을 클릭한다.
2. 수정하기 위한 파일보기의 상단우측 모서리에서 :pencil2:연필 상징을 클릭한다.
3. 편집기에서, 여기저기를 스스로 약간 기록하라.
4. 자신의 변경사항을 묘사하는 지르기(commit)알림을 기록한다.
5. **Commit changes(변경사항 지르기)** 버튼을 클릭한다.

이것은 자신의 _**readme-edits**_ 가지에 있는 README 파일만 변경한다, 그래서 지금 이 가지는 _**줄기(master)**_ 와 다른 내용을 포함한다.

## 단계 4. 요청끌어오기 열기

멋지게 편집했다! 이제 _**줄기(master)**_ 에서 벗어난 가지에서 변경됐다, 자신의 _요청끌어오기(pull request)_ 를 열 수 있다.

요청끌어오기(pull request)는 깃허브상에서 협업의 핵심이다. _요청끌어오기(pull request)_ 를 열면, 자신의 변경사항과 누군가가 검토한 요청을 제안한다 그리고 자신의 이바지에 끌어온다 그리고 그 가지에 합치기를 한다. 요청끌어오기는 _다름(diff)_ 을 보여준다, 또는 차이(difference), 양쪽 가지에서 내용의. 변경, 추가, 그리고 빠짐은 녹색과 적색으로 보여준다.

지르기(commit)를 하자마자, 요청끌어오기(pull request)와 토론 시작을 열 수 있다, 심지어 코드가 끝나기도 전에.

By using GitHub’s [@mention system](https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar) in your pull request message, you can ask for feedback from specific people or teams, whether they’re down the hall or 10 time zones away.
깃허브의 [@언급하기 체제](https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar)를 자신의 요청끌어오기(pull request) 알림에 사용함으로써, 특정한 사람이나 단체로부터 응답을 요청할 수 있다, 나락으로 떨어지던지 아니면 10시간 차이가 있던지 어떤지.

당신은 더불어서 자신의 저장소에서 요청당겨오기를 열 수 있다. 이것은 더 큰 과제를 작업하기 전에 깃허브 흐름을 배우기 위한 좋은 방법이다.

### README에 대한 변경을 위하여 요청당겨오기를 연다

_큰판에 대한 이미지는 클릭한다_

#### 1 단계

**pull request(요청끌어오기)** 탭을 클릭한다, 그런다음 요청끌어오기(pull request) 페이지에서, **new pull request(새요청끌어오기)** 의 녹색버튼을 클릭한다.  
<p align="center"><img width="70%" src="images/pr-tab.gif" /></p>  

#### 2 단계
**Example Comparisons(본보기 비교)** 상자에서 자신이 만든 가지(branch)를 선택한다, _**readme-edits**_, _**줄기(master)**_ (원본)와 비교하기 위하여.  
<p align="center"><img width="70%" src="images/pick-branch.png" /></p>  

#### 3 단계
비교페이지의 다름에서 자신의 변경사항을 살펴본다, 그들이 원하는 제안을 확실히 한다.  
<p align="center"><img width="70%" src="images/diff.png" /></p>  

#### 4 단계
원하는 제안의 변경사항이 만족 스럽다면, 큰 녹색의 **Create Pull Request(요청끌어오기 생성)** 버튼을 클릭한다.  
<p align="center"><img width="70%" src="images/create-pr.png" /></p>  

#### 5 단계
요청끌어오기(pull request)의 제목을 지정한다 그리고 자신의 변경사항의 간략한 묘사를 기록한다.  
<p align="center"><img width="70%" src="images/pr-form.png" /></p>  

자신의 알림이 끝나면, **Create pull request(요청끌어오기 생성)** 을 클릭한다!

> 조언: 당신은 [그림상징](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji)과 [끌기와 이미지 떨구기와 gif](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/)에 주석달기와 요청끌어오기를 할 수 있다.

## 단계 5. 자신의 요청끌어오기를 합친다

이 마지막 단계에서, 자신의 변경사항을 함께 가져올 시간이다 - 자신의 _**readme-edits**_ 가지를 _**줄기(master)**_ 의 가지에 합치기 하기.

1. _**줄기(master)**_ 에 변경사항을 합치기 위하여 녹색의 **Merge pull request(요청끌어오기 합치기)** 버튼을 클릭한다.
2. **Confirm merge(합치기 확인)** 을 클릭한다.
3. 계속한다 그리고 가지를 삭제한다, 변경사항이 포함되었기 때문에, 보라색 상자에 달린 **Delete branch(가지 삭제)** 버튼 으로.

<p align="center"><img width="70%" src="images/merge-button.png" /></p>
<p align="center"><img width="70%" src="images/delete-button.png" /></p>
 
### 축하한다! Celebrate!
이 가르침을 완료함으로써, 깃허브에서 과제를 생성하고 요청끌어오기를 하는 방법을 배웠다! :tada::octocat::zap:

여기에 있는것은 이 가르침에서 성취한것이다:
- 공개자료 저장소 생성
- 새 가지(branch) 시작과 관리
- 파일을 변경하고 깃허브에 변경사항 지르기(commit)
- 요청끌어오기(Pull Request)의 열기와 관리

자신의 깃허브 윤곽(profile)을 본다 그리고 자신의 새로운 이바지 [사각형(contribution squares, 영문)](https://help.github.com/articles/viewing-contributions)을 볼 수 있다!

요청끌어오기(Pull Request)의 능력에 대해 더 배우려면, 우리는 [깃허브 흐름 안내(영문)](http://guides.github.com/overviews/flow) 읽기를 권고한다. 또한 당신은 [깃허브 탐험(영문)](http://github.com/explore)을 방문할 수 있다 그리고 공개자료과제(Open Source project)에 참여하자 :octocat:

> 조언: 다른 [안내(영문)](http://guides.github.com/), 깃허브를 시작하는 방법에 대한 더많은 것은 [유튜브채널(영문)](http://youtube.com/githubguides)과 [주문 수련(On-Demand Training, 영문)](https://services.github.com/on-demand/) 를 확인하시오.

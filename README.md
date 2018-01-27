:kr: 깃허브란 무엇인가?

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

이 가르침을 완료하기 위해서는, **GitHub.com의 계정** 과 인터넷접근이 필요하다. 코드의 작성방법은 알 필요가 없다, 명령행을 사용한다, 또는 Git(판조절 깃허브 소프트웨어는 내장(제공)됨)을 설치한다.  

> 조언: 분리된 창(또는 탭)에 이 길잡이를 연다 그러면 가르침의 단계를 완료하는 동안 볼수 있다.

## 단계 1. 저장소 생성

**저장소(repository)는** 하나의 과제를 구성하기 위하여 일반적으로 사용한다. 저장소는 폴더와 파일, 이미지, 비디오, 스프레드쉬트, 그리고 자료집합을 포함할 수 있다-과제에 필요한 모든것. 우리는 _README(나를봐)_ 를 포함하는것을 권고한다, 또는 과제에 대한 정보가 포함된 파일. 깃허브는 쉽게 새로운 저장소를 동시에 추가할 수 있다. _또한 권리(license)파일 같은 다른 공통 선택사양도 제공한다._

자신의 _hello-world_ 저장소는 아이디어, 자원을 저장, 더불어서 심지어 다른사람과 공유하고 의논하는 장소가 될 수 있다.

### 새로운 저장소를 생성하기 위하여

<p align="center"><img width="90%" src="images/저장소 생성.png" /></p>

1. 상단우측 모서리에, 자신의 아바타 또는 신원상징 옆을, 클릭하고 **New repository(새 저장소)** 를 선택한다.
2. **Repository name(저장소 이름)** 을 "hello-world"로 한다(2018년 01월 24일 현재 한글로된 저장소 이름은 지원이 안된다)
3. **Description(묘사)** 에 짧게 묘사한다.
4. **Initialize this repository with a README(README를 포함하여 이 저장소를 초기화)** 를 선택한다.

**Create repository(저장소 생성)** 를 누른다. :tada:

## 단계 2. 가지 생성

**가지뻗기(Branching)** 는 저장소의 다양한 판(version)을 한번에 작업하는 방법이다.

기본적으로 저장소는 _줄기(마스터, master)_ 라는 이름인 하나의 가지(branch)가 있다 이것은 확정된가지로 인정한다. 우리는 실험과 편집하기를 위하여 가지를 사용한다 _줄기(master)_ 로 지르기(커밋, commit)를 하기 전에.

_줄기(master)_ 에서 가지를 생성할 때, 그 시점의 _줄기_ 로 자신의 복사본, 또는 스냅샷(snapshot)을 만든다. 만약 자신의 가지에서 작업하는 동안 다른 누군가가 _줄기_ 를 변경했다면, 갱신된 것들을 자신의 가지에 끌어오기(pull)를 할 수 있다.

이 도형이 보여주는 것:
- _줄기(master)_ 라는 가지
- _특징(feature)_ 라고 하는 새가지(이 가지에서 '특징 작업'을 하기 때문이다)
- _줄기(master)_ 로 합치기(merge) 전에 _특징(feature)_ 을 가지는 여정

<p align="center"><img width="90%" src="images/저장소 가지.png" /></p>

다른판의 파일을 저장한 적이 있는가? 이런것 처럼:
- _story.txt_
- _story-joe-edit.txt_
- _story-joe-edit-reviewed.txt_

가지(branch)는 깃허브 저장소에서 비슷한 목적을 달성한다.

여기 깃허브에서, 우리 개발자, 저자, 그리고 설계자는 버그 수정을 위하여 가지(branch)를 사용한다 그리고 _줄기(master)_ (라고 생성된) 가지와 분리된 특징 작업을 한다. 변경사항이 준비되면, 그 가지(branch)를 _줄기(master)_ 로 병합한다.

### 새가지 생성을 위하여
<p align="center"><img width="90%" src="images/나를봐-수정(readme-edits).gif" /></p>

1. _hello-world_ 라는 자신의 새저장소로 이동한다.
2. 파일목록의 상단에 있는 _branch:master_ 라는 떨굼(드롭다운)을 클릭한다.  
3. 가지이름을 타자한다, _readme-edits_, 문자상자에 새가지로.
4. _Create branch_ 라는 청색 상자를 클릭한다 아니면 자신의 키보드에서 “Enter”키를 누른다.

이제 2개의 가지를 가진다, _줄기(master)_ 와 _readme-edits_. 그것은 똑같아 보인다, 하지만 오래가지 않는다! 새가지에 우리의 변경사항을 추가한 다음에는.

## 단계 3. 변경하고 지르기(commit)하기

브라보! 이제, 당신은 자신의 _readme-edits_ 라는 가지에 대한 코드보기에 있다, 이것은 _줄기(master)_ 의 사본이다. 몇가지 사항을 수정해 보자.

깃허브 에서는, 저장된 변경사항을 지르기(commit)라고 한다. 모든 지르기는 연관된 지르기(commit) 알림 가지고 있다, 이것은 특별한 변경이 이루어진 이유를 설명하는 묘사이다. 지르기(commit) 알림은 자신의 변경이력을 채집한다, 그래서 자신이 한 일과 이유를 다른 참여자가 이해할 수 있다.

### 변경하고 지르기(commit)하기
<p align="center"><img width="90%" src="images/지르기(commit).png" /></p>

1. _README.md_ 파일을 클릭한다.
2. 수정하기 위한 파일보기의 상단우측 모서리에서 :pencil:연필 상징을 클릭한다.
3. 편집기에서, 여기저기를 스스로 약간 기록하라.
4. 자신의 변경사항을 묘사하는 지르기(commit)알림을 기록한다.
5. **Commit changes(변경사항 지르기)** 버튼을 클릭한다.

이것은 자신의 _readme-edits_ 가지에 있는 README 파일만 변경한다, 그래서 지금 이 가지는 _줄기(master)_ 와 다른 내용을 포함한다.

## 단계 4. 요청끌어오기 열기

Nice edits! Now that you have changes in a branch off of master, you can open a pull request.

Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams, whether they’re down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub Flow before working on larger projects.

### Open a Pull Request for changes to the README

Click on the image for a larger version

Step | -  
------------ | ------------  |  
Click the  Pull Request tab, then from the Pull Request page, click the green New pull request button. | <p align="center"><img width="50%" src="images/pr-tap.gif" /></p>  

In the Example Comparisons box, select the branch you made, readme-edits, to compare with master (the original). | <p align="center"><img width="50%" src="images/pick-branch.png" /></p>  

Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit. | <p align="center"><img width="50%" src="images/diff.png" /></p>  

When you’re satisfied that these are the changes you want to submit, click the big green Create Pull Request button. | <p align="center"><img width="50%" src="images/create-pr.png" /></p>  

Give your pull request a title and write a brief description of your changes. | <p align="center"><img width="50%" src="images/pr-form.png" /></p>  

When you’re done with your message, click Create pull request!

> Tip: You can use emoji and drag and drop images and gifs onto comments and Pull Requests.

## 단계 5. 자신의 요청끌어오기를 합친다

In this final step, it’s time to bring your changes together – merging your readme-edits branch into the master branch.
Click the green Merge pull request button to merge the changes into master.
Click Confirm merge.
Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.
 
Celebrate!
By completing this tutorial, you’ve learned to create a project and make a pull request on GitHub!   
Here’s what you accomplished in this tutorial:
Created an open source repository
Started and managed a new branch
Changed a file and committed those changes to GitHub
Opened and merged a Pull Request
Take a look at your GitHub profile and you’ll see your new contribution squares!
To learn more about the power of Pull Requests, we recommend reading the GitHub Flow Guide. You might also visit GitHub Explore and get involved in an Open Source project 

Tip: Check out our other Guides, YouTube Channel and On-Demand Training for more on how to get started with GitHub.
Last updated April 7, 2016
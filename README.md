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

이 가르침을 완료하기 위해서는, GitHub.com의 계정과 인터넷접근이 필요하다. 코드의 작성방법은 알 필요가 없다, 명령행을 사용한다, 또는 Git(판조절 깃허브 소프트웨어는 내장(제공)됨)을 설치한다.  

> 조언: 분리된 창(또는 탭)에 이 길잡이를 연다 그러면 가르침의 단계를 완료하는 동안 볼수 있다.

## 단계 1. 저장소 생성

A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. We recommend including a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.  
**저장소(repository)는** 하나의 과제를 구성하기 위하여 일반적으로 사용한다. 저장소는 폴더와 파일, 이미지, 비디오, 스프레드쉬트, 그리고 자료집합을 포함할 수 있다-과제에 필요한 모든것. 우리는 _README(나를봐)_ 를 포함하는것을 권고한다, 또는 과제에 대한 정보가 포함된 파일. 깃허브는 쉽게 새로운 저장소를 동시에 추가할 수 있다. _또한 권리(license)파일 같은 다른 공통 선택사양도 제공한다._

Your hello-world repository can be a place where you store ideas, resources, or even share and discuss things with others.
자신의 hello-world 저장소는 아이디어, 자원을 저장, 더불어서 심지어 다른사람과 공유하고 의논하는 장소가 될 수 있다.

### 새로운 저장소를 생성하기 위하여
<p align="center"><img width="100%" src="images/저장소 생성.png" /></p>

1. 상단우측 모서리에, 자신의 아바타 또는 신원상징 옆을, 클릭하고 **New repository** 를 선택한다.
2. **Repository name(저장소 이름)** 을 "hello-world"로 한다(2018년 01월 24일 현재 한글로된 저장소 이름은 지원이 안된다)
3. **Description(묘사)** 에 짧게 묘사한다.
4. **Initialize this repository with a README(README를 포함하여 이 저장소를 초기화)** 를 선택한다.

**Create repository(저장소 생성)** 를 누른다. 

## 단계 2. 가지 생성

Branching is the way to work on different versions of a repository at one time.  

By default your repository has one branch named master which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.  

When you create a branch off the master branch, you’re making a copy, or snapshot, of master as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates.  

This diagram shows:
- The master branch
- A new branch called feature (because we’re doing ‘feature work’ on this branch)
- The journey that feature takes before it’s merged into master 

Have you ever saved different versions of a file? Something like:
- story.txt
- story-joe-edit.txt
- story-joe-edit-reviewed.txt

Branches accomplish similar goals in GitHub repositories.  

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our master (production) branch. When a change is ready, they merge their branch into master.

### To create a new branch
<p align="center"><img width="100%" src="images/저장소 가지.png" /></p>

1. Go to your new repository hello-world.
2. Click the drop down at the top of the file list that says branch: master.
3. Type a branch name, readme-edits, into the new branch text box.
4. Select the blue Create branch box or hit “Enter” on your keyboard.

Now you have two branches, master and readme-edits. They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

## 단계 3. 만들고 지르기(commit)로 변경한다 Make and commit changes

Bravo! Now, you’re on the code view for your readme-edits branch, which is a copy of master. Let’s make some edits.
On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.
Make and commit changes
Click the README.md file.
Click the  pencil icon in the upper right corner of the file view to edit.
In the editor, write a bit about yourself.
Write a commit message that describes your changes.
Click Commit changes button.

These changes will be made to just the README file on your readme-edits branch, so now this branch contains content that’s different from master.

## 단계 4. 요청끌어오기 열기

Nice edits! Now that you have changes in a branch off of master, you can open a pull request.
Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.
As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.
By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams, whether they’re down the hall or 10 time zones away.
You can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub Flow before working on larger projects.
Open a Pull Request for changes to the README
Click on the image for a larger version
Step
Screenshot
Click the  Pull Request tab, then from the Pull Request page, click the green New pull request button.

In the Example Comparisons box, select the branch you made, readme-edits, to compare with master (the original).

Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit.

When you’re satisfied that these are the changes you want to submit, click the big green Create Pull Request button.

Give your pull request a title and write a brief description of your changes.

When you’re done with your message, click Create pull request!

Tip: You can use emoji and drag and drop images and gifs onto comments and Pull Requests.

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
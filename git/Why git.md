# Why Git?
---------
## 상황 1
13기 와이빅타 과제로 코딩을 하고 있는 와빅이
와빅이는 과제에서 구현하라고 하는 기능 5가지 중 4가지를 끝냈다.
그렇지만 마지막 기능을 추가하는 과정에서 이유 모를 오류가 발생해서 프로그램이 아예 동작하지 않는다.

> 어쩔 수 없지.. 4개만 하고 내야겠다!

</br>
엥! 근데 이게 무슨 일?

마지막 기능을 구현하면서 코드를 너무 많이 고쳐서 4개가 되던 `version`이 기억나지 않는다!
와빅이는 다 지우고 처음부터 해야하는 것일까?

------------------
## 와빅이의 선택
다행히 와빅이는 바보가 아니었다! 4개가 될 때의 `version`을 복사해서 가지고 있었다.

결국 와빅이의 폴더는...
> assi_1.py
> assi_1_last.py
> assi_2.py
> assi_last.py
> assi_real_last.py
> assi_real_real_last.py

_____________________________
## 상황 2
이번에는 와이빅타 프로젝트를 하기로 한 와빅이
그렇지만 코딩은 업무분담을 어떻게 나눠야 할지 모르겠다. 
결국 각자 해보고 결과가 잘나온 것으로 하기로 한 와빅과 친구들

그렇게 며칠 후, 서로 어떻게 하고 있는지 공유하기로 했다. 
> 좋아 그럼 카톡으로 python 파일 보내줄게!
> 
엥! 근데 이게 무슨 일?
파이썬 파일은 카톡으로 보낼 수 없는 확장자라고 한다.
그럼 귀찮게 이메일로 다른 3명의 조원에게 보내야 하나?
______________________
## 와빅이의 선택
와빅이는 바보가 아니었다! 확장자를 `zip`으로 압축해서 보내면 카톡에서도 보내지는 것이었다.

결국 와빅이의 카톡방은....
> 와빅이_결과.zip
> 태오_중간_결과.zip
> 와빅_태오것_수정.zip
> 현우_최종.zip
> 우리팀_최종.zip
> 우리팀_제출.zip
> 
_______________
# 이렇듯 코딩할 때에도 `버전관리`가 필요하다.
# $\rightarrow$ Git은 프로젝트의 `버전관리`를 위해 탄생한 VCS(Version Control System)이다.

_____________________
# Git 기본 개념
__________________
## Git이란?
Git은 폴더(프로젝트)에 들어있는 파일들의 변경사항을 기록합니다.
또한 Branch를 사용하여, 여러가지 다양한 버전으로 나누어 기록할 수 있게 해줍니다.
___________________
![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Git-Architechture-Git-Tutorial-Edureka-2-768x720.png)
_______________________
- Working directory
: Git 저장소로 사용되고 있는 프로젝트 폴더
- Staging Area
: Working directory 내에서도 실제로 기록하려고 하는 파일들
	- `git add assign.py`
: assign.py 라는 파일을 staging area에 기록한다.
- Local repo
: 실제 변경사항을 저장하는 저장소
	- `git commit -m 'first init'`
: `first init`이라는 메세지로 현재 staging area를 local repo로 저장한다.
__________________
## 예시



_______________________

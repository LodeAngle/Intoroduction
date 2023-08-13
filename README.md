# Introduction to Git&GitHub 
***
# 1. Git&GitHub 이용 목적
- 버전 컨트롤
- 과제 제출
- 코드 리뷰

## 1.1 버전(version)이란?
1. 원하는 시점(point in time)으로 이동 할 수 있게 해주는 것 → 버전
2. 메타데이터(metadata, 데이터를 설명해 주는 데이터) 
  - 파일 작성자(The author of the file)
  - 저장 위치(Where it is located)
  - 파일 형식(The file type)
  - 저장 시점(When it was last saved) 
<p align="center">
<img src="https://www.hanbit.co.kr/data/editor/20230512160223_whmadsed.png" width="70%" height="70%" alt="버전관리란?"> 
<br />
버전 관리란? (출처:hanbit.co.kr)  
  
3. 협업 프로젝트에서는 버전 관리가 특히 중요!
4. 버전 관리란?
  - 변경 사항 관리 → 변경 사항 기록/추적 
  - 동시 파일 개발 → 다른 버전 파일 결합  
  - 특전 버전 식별
  - 변경 사항 되돌리기 
<p align="center">
<img src="https://blog.kakaocdn.net/dn/8Fh1Y/btqzjg2OQx6/2ge5VZ8AV3O8H7niW0YW8K/img.png" width="400" height="300" alt="카카톡 예시">
<br />
카카오톡 버전 히스토리 (출처:https://tip-blog.tistory.com)  

## 1.2 Git과 GitHub란?
1. Git과 GitHub란?
  - Git(깃)은 **버전 관리 시스템**이고, GitHub(깃허브)는 Git으로 관리하는 **프로젝트를 업로드 및 다운로드 할 수 있는 사이트**
3. Git은
  - 일반적으로 사용되는 버전 관리 프로그램
  - 컴퓨터 프로그래밍 및 데이터 프로젝트
  - 오픈 소스
3. Git은 GitHub가 아니지만 일반적으로 Git은 GitHub와 함께 사용 됨
4. Git 호스팅 사이트: GitHub.com
<Br />

## 1.3 Git의 장점   
1. GitHub에 소스 코드를 올려 두면 시간, 공간의 제약 없이 협업할 수 있음
  - 다른 사람 컴퓨터와 동기화 가능
2. 프로젝트를 공개 저장소로 만들면 전 세계 개발자와 협업할 수 있음
3. 공개 저장소에 저장(오픈 소스)해 두면 파일을 잃어버리지 않음
4. 깃 없는 세상?
  - 변경 내역 확인이 어려움
  - 버전을 되돌리기 어려움
  - 협업이 어려움

<p align="center">
<img src="https://i0.wp.com/leechoong.com/wp-content/uploads/2017/12/101-6.png?w=618" width="300" height="150" alt="버전관리 중요성 설명용">
<br />
버전 관리의 중요성 (출처:http://leechoong.com/posts/2017/git_vcs/)

# 2. Git 시작하기 
## 2.1 Git 설치하기
- Git 설치 주소 [Link](https://git-scm.com) 
- Git 설치부터 설치 확인하기까지 참고 [Link](https://allhpy35.tistory.com/38)   

## 2.2 Git 초기설정
- "이름"과 "이메일"설정 [Link](https://articles09.tistory.com/48)  

# 3. Git 처리구조
1. Git은 4개의 주요 공간으로 구성되어 있음
<p align="center">
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbwH6Ln%2Fbtq3z4NgrB1%2F6DfZ5X5s3doQjxRo3kHeN1%2Fimg.png"  width="600" height="350" alt="Git 처리 구조">
<br />
Git의 처리 구조 (출처:https://jforj.tistory.com/119)  

2. 용어 설명(수정 전) 
- Working Directory: 개발자의 현재 시점으로 소스코드를 수정하며 개발하는 공간을 의미
- Staging Area: Working Directory에서 작업한 파일을 Local Repository에 전달하기 위해 파일들을 분류하는 공간 
- Local Repository: 로컬 저장소이며 작업한 파일들을 저장해두는 내부 저장소 (.git 폴더)
- Remote Repository: 원격 저장소이며 인터넷으로 연결되어 있어 있는 외부 저장소 (웹 페이지에서 보이는 공간)
- Branch: Remote Repository의 현재 상태를 복사하여 master 브랜치와 별개의 작업을 진행할 수 있는 공간 (보통 브랜치를 생성하여 개발을 진행하고 개발을 완료하면 master 브랜치에 병합하여 개발 완료된 소스코드를 합침)
- Head: 현재 작업중인 브랜치의 최근 커밋된 위치
- Index: Staging Area를 의미

# 3. GitHub 시작하기
## 3.1 GitHub 가입하기
- GitHub 가입하기 [Link](https://goddaehee.tistory.com/218)
- 학생인증 [Link](https://goddaehee.tistory.com/219)
## 3.2 Git 로컬 저장소와 GitHub 원격 저장소 연동하기
- GitHub는 원격에서 Git 저장소를 호스팅해주시는 서비스
- 로컬 컴퓨터에 있는 소스를 1) 백업 2) 협업 3) 공유하기 위해서는 github 사용이 필수
- 저장소 만들기부터 Push하기까지 [Link](https://leeporter.tistory.com/41)
- **작성 중**


# 4. 소스트리 시작하기
## 4.1 소스트리 설치하기
- 소스트리 설치 주소 [Link](https://www.sourcetreeapp.com)
- Git은 코딩? Sourcetree 사용하면 GUI로 Git을 사용 가능
    - 즉, 명령어 → 버튼/그래프/메뉴
    - 소스트리는 명령어 없이 깃 사용가능하도록 개발 된 클라이언트 프로그램
    - 다만, 깃의 고급 기능을 사용하기 위해서는 명령어 기반 학습이 필요 함
    - 우리는 Sourcetree 사용!
## 4.2 사용법(정리 중)

# 5. 과제 제출 방법
> 과제는 기한까지 새 branch를 파서 Pull Request (PR)로 제출하는 것을 원칙으로 한다.
> 과제 제출은
1. 자신의 이름으로 된 repository를 clone 받기
2. 새 branch를 파서 개발하고 pull request 날리기 (브랜치 이름은 과제 번호와 이름-학번으로 구성, 예시) project1-sungju-park-22000020)
3. commit message를 아무렇게나 기술하지 않고, 브랜치 이름으로 commit 하기

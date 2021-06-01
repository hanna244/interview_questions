# 기술 면접 

## 기술 면접 질문 

### HTML 
1. [em i strong 같은 경우 클래스 선택자가 아닌 요소 선택자를 사용했는데 왜 그렇게 사용했는가? ](#q-h01-기술질문)
1. [접근성 공식 사이트를 직접들어가서 관심있게 본 적이 있는가?](#q-h02-기술질문)
    - WCAG 2.2가 21년도 9월에 출시 될 예정이다. 2월에 초안은 나옴 
    - 면접 보기 전에 관심이 있어서 들어갔는데 ~~ 하단에 네 
1. ["role="text"를 사용한 이유는?](#q-h03-기술질문)
1. [v왜 img 태그를 사용했는가?](#q-h04-기술질문)
1. [v`<img>`에 width, height 값을 주었는데 왜 적용하였는가?](#q-h05-기술질문)
1. [v만약 `<img>`의 너비와 높이를 바꾸려면 어떻게 해야하는가?](#q-h06-기술질문)
1. [](#q-h07-기술질문)

### CSS 
1. [왜 css 파일을 쪼개서 작성했는가? 성능 문제는 어떻게 해결할 것인가?](#q-c01-기술질문)
1. [css 변수를 사용할 때 크로스 브라우징은 어디까지 고려했는가?](#q-c02-기술질문)
1. [노말라이즈를 왜 사용해요?](#q-c03-기술질문)
    - 브라우저 간의 일관성을 유지하기 위해서 사용한다.
    - 다른 초기화 방법은 없을까요? resetting과 노말라이즈를 사용할 수 있다. 
1. [왜 body 요소에 스타일을 주었나요?](#q-c04-기술질문)
1. [왜 다트 사스를 사용했는가?](#q-c05-기술질문)
  현재 해당 시안은 모바일, 시안이고 고정형으로 만들기 위해 바디에 
1. [scss과 css의 차이점](#q-c06-기술질문)
    - BEM표기법을 사용하면 중첩 사용 가능 심플한 HTML 클래스 설정 가능, mixin을 사용하여 빠른 작업 가능, 유지 보수에 좋음(왜? 위치를 찾기 쉬움)
1. [css repaint의 과정](#q-c07-기술질문)
1. [스킵네비게이션의 본래 목적과 퀵링크와의 차이](#q-c08-기술질문)

### 기타 
1. [앞 뒤 맥락이 맞지 않는다. 앞에서는 도구를 사용하지 않는다고 해놓고 왜 VSCode에서는 도구에 의존하려고 하는가?](#q-e01-기술질문)
1. [왜 컴포넌트 방식으로 쪼개서 사용했는가?](#q-e02-기술질문)
    - 리액트를 공부했고 컴포넌트 주도 방식을 사용하다보니 CDD 방식을 이번 과제에서도 적용해 보았다. 
1. [반응형 작업 시 어려웠던 점은 무엇인가?](#q-e03-질문)
1. [과제 페이지에서는 로고가 단 한 번 사용되는데 컴포넌트로 만들 이유가 있었을까?](#q-e04-질문)
1. [v무엇을 중심으로 프로젝트를 풀어나갔는가?](#q-e05-기술질문)
1. [v컴포넌트를 어떻게 관리해야 한다고 생각하는가?](#q-e06-기술질문)
    - 이 질문은 CSS만을 사용한 컴포넌트, React 컴포넌트 질문인지 확인하고 답변 
1. [v폴더 구조를 이렇게 설계한 이유가 있는가?](#q-e07-기술질문)
    - 이 질문은 CSS를 모듈화 하여 작성한 폴더 구조 때문에 받은 질문이다. 
1. [프로젝트 진행 시 어려웠던 점을 이야기해보세요](#q-n08-일반질문)
1. [가장 기억에 남는 이슈](#q-n09-일반질문)



## 기술 면접 답변 

### HTML 

#### Q-H01. 기술질문 
<details open>
  <summary>em i strong 같은 경우 클래스 선택자가 아닌 요소 선택자를 사용했는데 왜 그렇게 사용했는가?</summary>
  
</details>

#### Q-H02. 기술질문 
<details open>
  <summary>접근성 공식 사이트를 직접들어가서 관심있게 본 적이 있는가?</summary>
  
</details>

#### Q-H03. 기술질문 
<details open>
  <summary>"role="text"를 사용한 이유는?</summary>
  
</details>

#### Q-H04. 기술질문 
<details open>
  <summary>왜 img 태그를 사용했는가?</summary>
  
</details>

#### Q-H05. 기술질문 
<details open>
  <summary>v`<img>`에 width, height 값을 주었는데 왜 적용하였는가?</summary>
  
</details>

#### Q-H06. 기술질문 
<details open>
  <summary>v만약 `<img>`의 너비와 높이를 바꾸려면 어떻게 해야하는가?</summary>
  
</details>

---
### CSS  

#### Q-C01. 기술질문 
<details open>
  <summary>왜 css 파일을 쪼개서 작성했는가? 성능 문제는 어떻게 해결할 것인가?</summary>
  
</details>

#### Q-C02. 기술질문 
<details open>
  <summary>css 변수를 사용할 때 크로스 브라우징은 어디까지 고려했는가?</summary>
  
</details>

#### Q-C03. 기술질문 
<details open>
  <summary>노말라이즈를 왜 사용해요?</summary>
  
</details>

#### Q-C04. 기술질문 
<details open>
  <summary>왜 body 요소에 스타일을 주었나요?</summary>
  
</details>

#### Q-C05. 기술질문 
<details open>
  <summary>왜 다트 사스를 사용했는가?</summary>
  
</details>

#### Q-C06. 기술질문 
<details open>
  <summary>scss과 css의 차이점</summary>
  
</details>

#### Q-C06. 기술질문 
<details open>
  <summary>css repaint의 과정</summary>
  
</details>

#### Q-C06. 기술질문 
<details open>
  <summary>스킵네비게이션의 본래 목적과 퀵링크와의 차이</summary>
  
</details>
---

### Etc     

#### Q-E01. 기술질문 
<details open>
  <summary>앞 뒤 맥락이 맞지 않는다. 앞에서는 도구를 사용하지 않는다고 해놓고 왜 VSCode에서는 도구에 의존하려고 하는가?</summary>
  
</details>

#### Q-E02. 기술질문 
<details open>
  <summary>왜 컴포넌트 방식으로 쪼개서 사용했는가?</summary>
  
</details>

#### Q-E03. 기술질문 
<details open>
  <summary>반응형 작업 시 어려웠던 점은 무엇인가?</summary>
  
</details>

#### Q-E04. 기술질문 
<details open>
  <summary>과제 페이지에서는 로고가 단 한 번 사용되는데 컴포넌트로 만들 이유가 있었을까?</summary>
  
</details>

#### Q-E05. 기술질문 
<details open>
  <summary>v무엇을 중심으로 프로젝트를 풀어나갔는가?</summary>
  
</details>

#### Q-E06. 기술질문 
<details open>
  <summary>v컴포넌트를 어떻게 관리해야 한다고 생각하는가?</summary>
  
</details>

#### Q-E07. 기술질문 
<details open>
  <summary>v폴더 구조를 이렇게 설계한 이유가 있는가?</summary>
  
</details>

#### Q-E08. 기술질문 
<details open>
  <summary>프로젝트 진행 시 어려웠던 점을 이야기해보세요</summary>
  
</details>

#### Q-E09. 기술질문 
<details open>
  <summary>가장 기억에 남는 이슈</summary>
  
</details>

## 과제 제출 전 체크 사항 

### 점검 
- 프론트엔드 개발자면서 왜 라이트 하우스 검사를 했는가? 
- 깃북의 파일트리 다시 봐라 제대로 작성 요망 
- package 파일 설정 
- htmlhintrc 설정 true로 설정하기 
- 버튼 요소에 적절한 버튼의 기능을 작성했는가? 
  - aria-label은 스크린 리더가 읽지 못하는 문제가 발생 할 수 있기 때문에 title을 같이 작성해야한다. 

### sass 
- 주석도 컴파일 되지 않도록 하기 (필요한 주석은 남기고 아닌 주석은 남김)

### 패키지
- 배포 할거 아님 버전 노 필요 
- 컴파일 npm sass -h 
- npm run compile 명령어를 사용하려면 -- 대시 2개를 사용해야 한다. 
- 과제 제출로만 사용하니 프라이베잇으로 설정 
- 빌드 명령어를 사용해서 스타일 코드를 압축한다. 
  - 배포 할 것도 아닌데 왜 빌드 명령을 사용했는가? 
    왜냐하면 dist 폴더 해당 html을 만들었고 압축을 했을 때 코드의 용량이 줄어들기 때문이다. 
- 어떻게 서버를 구동하는가? npm live-server을 사용한다. 
  - live-server 
  - 단, live-server 
- npm-run-all을 사용하면 npm 스크립트를 병렬식으로 실행 가능하다. 
  - npm -p 를 사용하면 npm-run-all
- node_modules를 추가 했는가? 
  - 나중에 라이브러리를 추가하여 확장하여 사용할 수 있는 것을 고려했다.  

> npm-run-all 이란 npm을 병렬식 또는 직렬식으로 실행하는 것을 도와주는 npm 도구이다. 
> 라이브 서버와 사스 구동 시 두 개의 패키지가 한 번에 실행 할 수 있도록 한다. 
> npm-p 을 사용하면 병렬식으로 실행되고 npm-s 를 사용하면 직렬식으로 실행된다. 


# Q1. 질문
JS 오류는 콘솔 패널에서 표시되므로 작업 할 때, 콘솔 패널을 확인하며 작업을 해야하나요?
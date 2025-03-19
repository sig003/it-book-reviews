# it-book-reviews
IT 도서에 대한 리뷰들

## 리뷰
**트래픽을 쓸어 담는 SEO 마케팅** ❤️❤️❤️
- 검색엔진에 유료인 키워드 광고보다 seo를 통한 검색이 8.5배 높은 전환율 보임
- 타깃 키워드 넣어도 잘 안됨
- 구글이 검색창에 입력한 키워드가 정확히 담긴 페이지를 보여주는 게 아니라 해당 키워드의 의미를 이해한 후 관련 콘텐츠 중 가장 정확하고 품질이 좋다고 판단되는 페이지를 보여주기 때문
- 테크니컬 seo는 다들 너무 잘해서 완벽하게 해야 그나마 가능성 있음
- 백링크는 수보다 어디서 받았는지 질이 더 중요
- 웹사이트가 느리면 크롤러도 느려짐
- 301 리디렉션
-- 도메인이나 url을 영구적으로 변경할 때 사용
-- 새로운 url을 색인에 저장하고 이전 색인은 삭제
-- 이전의 정보를 이어받아 동일 키워드로 비슷한 순위 유지하고 페이지 랭크도 같은 수치 유지
- 302 리디렉션
- 사이트를 일시적으로 옮길 때 사용
- 새로운 url 색인 저장하지만 이전 색인 안 지움
- 하지만 302가 장기간 유지되면 301리디렉션으로 판단해 기존 색인 삭제
- 캐노니컬 태그는 대표 url 지정하는 것
- 중복 콘텐츠 있어도 색인돼야 할 대표 url 지정하는 것
- 책의 타깃이 개발자 + 마케터
- 타깃이 뚜렷하지 않아 이런저런 내용이 많음
<br />

**한권으로 끝내는 실전 LLM 파인튜닝** ❤️
- 런팟 클라우드 기반의 gpu 컴퓨팅 플랫폼
- multi gpu 사용 가능
- PyTorch로 llm 모델을 만드는 내용의 책
- 내 수준에서 읽을 수 없는 상위 책이었음
- 평가 불가
<br />

**그로킹 알고리즘** ❤️❤️❤️❤️❤️
- 알고리즘의 실행 시간이 얼마나 걸리는지만 고려할 게 아니라 리스트의 크기가 증가할 때 실행 시간이 어떻게 증가하는지도 파악해야 함
- 이것이 빅오 표기법을 사용하는 이유
- 빅오 표기법은 알고리즘이 얼마나 빠른지 말해줌
- 빅오 표기법은 속도를 시간 단위로 세지 않음
- 연산 횟수를 비교하기 위한 것이므로 수행해야 할 일이 많아질 때 알고리즘에 걸리는 시간이 어떤 식으로 증가하는지 알 수 있음
- O(n): n은 연산 횟수
- 알고리즘이 작동하기 위해 필요한 연산 횟수 나타냄
- 알고리즘의 속도는 시간이 아니라 연산 횟수가 어떻게 증가하는 지로 측정
- 트리에서 무언가 검색할 때 데이터를 찾으려면 물리적 객체가 움직여야 함
- 이게 디스크 탐색시간
- b 트리는 탐색 완료 후 한 번에 여러 정보를 메모리에 저장함
- 이진 트리보다 더 많은 키와 자식을 가질 수 있어 크기가 큼
- 대신 읽어 들이는데 많은 시간을 소요하지만 한 번에 많은 데이터를 읽어들여 검색 횟수는 줄어듦
- 데이터베이스가 디스크에서 데이터 검색에 많은 시간 소모하므로 b 트리를 사용하는 게 적절함
- 알고리즘과 관련해 좋은 책
- 쉽게 설명이 잘 되어 있는 책이지만 한 권으로 끝나는 종류의 책은 아님 
- 보완할 책은 필요함
<br />

**랭체인 완벽 입문** ❤️❤️❤️
- 2024년 출간된 책이지만 2023년 9월 기준으로 작성됨
- chatgpt 3.5 기준
- chatgpt api는 토큰 기준 종량제
- 영어는 1단어 1토큰
- 한국어는 1문자당 1~2 토큰
- 비용은 입력 토큰과 출력 토큰에서 모두 발생
- few-shot prompt
-- 언어 모델이 수행해야 할 작업을 지시하고 그 작업의 입력과 출력 예시를 제시
-- 그러면 언어 모델은 예시를 통해 작업 패턴을 학습하고 유사한 출력을 생성함
-- ex) 
--- 예시: 소문자 입력을 대문자로 변환하시오
---입력: hello
--- 출력: HELLO
-- 위와 같이 지시하면 언어 모델이 유사하게 출력값을 냄
-- 구체적인 예시를 제시해서 인간이 상상하는 출력물에 가까운 결과를 생성할 수 있음
- 언어 모델은 학습한 정보만 답변함
- 학습하지 않은 정보는 답변 못함
- 이 문제를 해결하기 위해 RAG(Retrieval-Augmented Generation) 사용
- 사용자 입력과 관련한 내용을 외부 데이터베이스 등에서 검색
- 언어 모델이 모르는 정보에 대답하는 기법
- llm에 대한 지식 전달을 깔끔하게 수행하는 책
- 다만 예제들이 2023년 기준이라 아쉬움
<br />

**쉽고 빠르게 익히는 실전 LLM** ❤️❤️
- 가독성에 문제가 있음
- 눈에 잘 안 들어옴
- LLM 초보라서 그런 거라면 할 말 없지만
- 그렇다면 이 책의 타깃 구독자는 전문가인가?
<br />

**네트워크 교과서** ❤️❤️
- 네트워크 기초 지식에 대해 설명하는 책
- CS 기초 복습하려고 봤음
- CS 지식은 잊을만하면 복습해 줘야 함 
- 책이 쉬울 것 같은데 이상하게 눈에, 머리에 잘 안 들어옴
- 번역서라 그런 걸까?
<br />

**읽고 나면 진짜 쉬워지는 자료 구조** ❤️❤️
- pseudo 코드 위주라 실습해 볼 게 없는 게 아쉬움
- 번역본이라 글자는 많고 가독성이 그다지 좋지 않음
- 이해가 잘 되는 것도 아님
<br />

**Hey, 파이썬! 생성형 AI 활용 앱 만들어 줘** ❤️❤️❤️
- 파이썬 기본 사용법
- 이후 chat gpt api를 연동하는 방법
- 랭체인 사용법
- 다양한 ai 서비스 만드는 법 소개함
- 2024년 3월에 출간된 책이라 과거형 내용들이 있음
- 그래도 gpt 연동 법 기초 개념 익히기에 좋음
<br />
  
**유니티 교과서** ❤️❤️❤️
- 유니티 초보자를 대상으로 하는 책
- C# 코딩도 나오는데 프로그래밍 초보자도 접근할 수 있는 수준으로 만들어졌음
- IT 분야는 업데이트가 빨라 책과의 괴리가 발생함
- 이 책도 가장 최근 개정판인데 유니티가 업데이트되면서 메뉴명이 달라진 것들이 조금 있음
- 아직은 문제없이 할 수 있는 수준 
- 책의 구성은 따라 하기 보다 스스로 게임을 만들어 갈 수 있는 방법에 초점을 맞추고 있음
- 기초를 배울 수는 있는데 다 따라 하고 나면 기억에 남는 건 별로 없음
- 먼저 무엇인가 만들어 나가면서 책에서 모르는 것을 찾는 게 가장 좋은 프로그래밍 책 활용법이라 생각함
<br />

**자바스크립트 + 리액트 디자인 패턴** ❤️❤️
- 굳이 디자인 패턴 고집하지 않아도 된다고 함
- 패턴이란 소프트웨어 설계에서 반복되는 문제와 주제에 적용할 수 있는 재사용 가능한 템플릿을 말함
- 패턴의 사용 이유
- 1) 검증되었음
- 2) 쉽게 재사용 가능
- 3) 알아보기 쉬움
- 4) 사소한 실수로 인한 큰 문제 방지
- 5) 특정 문제에 국한되지 않은 종합적 해결책 제시
- 6) 반복 피해 코드 양 줄임
- 7) 공통된 어휘 사용해 의사소통 원활
- 전역 변수 관리를 라이브러리 안 쓰고  싱글톤으로 하면 어떨까 생각했는데 싱글톤의 단점
- 1) 싱글톤 파악 어려움
- 2) 테스트 어려움
- 3) 사용이 어려움 등이 있고 
- 4) 리액트에서 context api 또는 리덕스 사용하라고 제안함
- 리액트는 MVC 프레임워크가 아님
- UI 구축을 위한 자바스크립트 라이브러리
- 주로 SPA 개발에 사용
- Next.js는 리액트를 기반으로 한 프레임워크
- 주로 SSR 구현에 사용
- MVC 프레임워크는 아니지만 SSR, SSG를 사용 시 MVC와 유사한 패턴으로 동작
- Next.js가 백엔드 역할을 수행하여 DB와 상호작용하고 뷰를 사전 렌더링 하면 이후부터 리액트의 반응형 기능을 통해 뷰를 동적 업데이트해서 전통적 MVC 형태로 동작
- 기초 개념 도서
- 리액트 내용은 맛보기처럼 곁들여져 있음
- 이런 유의 책은 갑자기 본론으로 넘어가 설명하면서 내가 뭘 읽고 있는지 길을 잃게 만듦
- 이 책도 마찬가지 어딘가에서 길을 잃었음
- 디테일을 보기보다 더 높은 곳에서 이런 게 있구나 전체를 바라봐야 함
- 그리고 내가 사용하는 패턴이 어떤 건지 어떤 게 나을지 비교해가며 봐야 함
<br />

**AWS 시스템 개발 스킬업** ❤️
- 내용이 매우 이상한 책
- 스킬업이라 해서 AWS 초보 이상의 내용이 있을 줄 알았는데 초보적인 내용만 가득함
- 번역도 뻑뻑해서 눈에 전혀 들어오질 않음
<br />

**예제로 배우는 Django 4** ❤️❤️❤️
- Django 관련 서적이 많지 않은데 오랜만에 나온(2023년) 비교적 최근의 서적
- 아쉬운 점
- Django 5 버전이 나왔는데 책은 4 버전 기준
- Django를 백엔드 api 서버로 많이 쓸 텐데 프론트, 백엔드 합쳐진 풀스택 예제 위주
<br />

**실전 스프링 부트 (Spring Boot in practice)** ❤️
- 초보를 위해 처음부터 차근차근 밟아나가는 스타일의 책은 아님
- 백과 사전식 구성
- 초보에게는 도움 안 됨
<br />

**그렇게 쓰면 아무도 안 읽습니다** ❤️
- UX 라이팅에 대한 얘기
- 제목만 보고 IT 책인지 전혀 몰랐음
- (편견이겠지만) 국문학과 출신이 쓴 책이라 그런지 간결한 맛이 없고 분량이 너무 길며 문체가 딱딱함
- 힙한 제목과 달리 본문은 교과서 같음  
<br />

**실패는 나침반이다** ❤️❤️❤️
- 커리어 후반기에는 나 자신에 집중
- ex) 갈 길이 멀기 때문에 나를 중심으로 커리어를 바라봐야 함 
- 일이 재미없으면 손에 쥔 거 버리고 새 방향 모색
- 잘하는 것과 좋아하는 것 중 좋아하는 것을  해라
- ex) 내가 뭘 잘하는지 알기 어렵고 좋아하는 걸 해봐야 후회 안 함
- 커리어 기복을 당연하게 생각해야
- ex) 잘 나갈 때도 있고 그렇지 않을 때도 있음 
- 꾸준히 우상향 할 수 있으면 됨
- 혼자서 잘 하려고 하지 말고 매니저와 소통하며 일해라. 안 그러면 엉뚱하게 일하고 시간만 흘러간다
- 실리콘 밸리의 경우 직원들이 매니저에게 본인에 대한 피드백과 승진에 대한 의견을 끊임없이 요구함, 스스로 판단하거나 검열하지 말고 매니저와 조율해라
- 취업 준비에 많은 시간 쏟지 마라
- 부케(부업) 하는데 너무 집중하지 마라
- 사람을 관리하는 매니저 역할을 꼭 해봐라
- 리더는 다른 사람을 통해 결과를 내는 사람
- 리더의 피드백 시 주의할 점
- 1) 한 번 얘기하고 알아듣길 바람
- 2) 다른 사람에게 들었다는 식으로 전달함
- 3) 장점과 단점을 섞어서 충격을 완화하려 함
- 4) 보디랭귀지로 불만 표출
- 5) 구체적인 상황만 짚으면 상대는 디테일에 빠짐, 짚어야 할 건 전체적인 태도
- 개발자 얘기보다 직장인 모두에게 해당하는 얘기들
- 가독성이 아쉬움
<br />

**객체지향 파이썬 프로그래밍** ❤️
- 내가 무슨 글을 읽고 있는 건지 모르겠음
- 읽을수록 헷갈림
- 번역의 문제 + 내용의 문제로 보임
<br />

**코딩도 하고 사장도 합니다** ❤️❤️❤️
- 오랜시간 개발자로 일했고 창업 후 소소한 성공까지의 경험담
- 회고록 또는 개발 회사 창업 가이드 느낌
- 스스로 회사를 차려 평생 잘리지 않는 직장을 가진다는 개념에 공감함
<br />

**육각형 개발자** ❤️❤️❤️
- 저자의 경험이 녹아있는 좋은 책이라고 느꼈음
- 내가 생각하던 것과 맞는 부분도 꽤 있었음
- 다만 이제는 식상하게 느껴지는 얘기도 많아서 끝까지 읽지는 못함
- 이런 유의 책을 너무 많이 읽었나?
<br />

**쉽게 시작하는 타입스크립트** ❤️❤️❤️❤️❤️
- 시중에 타입스크립트 책이 나올 때마다 거의 다 찾아봤음
- 하지만 그 어떤 책도 만족스럽지 못했음
- 어렵고 읽기 힘들고 타입스크립트 이해도를 조금도 향상시키지 못함
- 출판되는 책을 계속 찾아본 것도 책을 읽고 지식이 축척되지 않았기 때문
- 이번에도 의문스러운 눈초리로 책을 접했음
- 다 읽고 나서 그동안 읽었던 책들이 쓰레기였음을 느꼈음
- 왜 이제야 이런 책이 나온 거지?
- 가독성 좋고 이해하기 쉽고 타입스크립트에 대한 지식을 향상시킴
- 다른 책들이 타입스크립트를 위한 타입스크립트 책이라면 이 책은 실무에 필요한 타입스크립트 책임
- 사용하지도 않는 튜플 같은 내용이 없음
- 단점이라면 대상 독자를 자바스크립트 초보까지 설정했다는 점
- 굳이 이런 내용까지 넣어야 하나 싶은 내용들이 있음
- 그러나 장점에 비하면 단점은 무시해도 될 수준
- 타입스크립트 필독서로 지정해야 할 책
<br />

**현장에서 바로 써먹는 리액트 with 타입스크립트** ❤️❤️❤️❤️
- 출판사 지원을 받아 리뷰를 함
- 처음 지원을 받을 때는 리뷰를 할까 말까 고민을 했음
- 리액트 개발을 해봐서 초보는 아니고 또 근래에는 프론트 개발을 안 하고 있음
- 그래서 초보 대상 서적을 굳이 읽어야 하나 고민했음
- 그럼에도 리뷰를 결정한 이유는 새 책에 대한 호기심과
- 저자 블로그에서 도움을 받았던 기억이 있어서
- 저자분 블로그 쓰시는 거 보면 책도 충실하리라는 믿음이 있었음
- 근래에는 리액트 씬에서 Next.js가 표준처럼 사용되고 있음
- 하지만 Next를 쓰더라도 리액트를 먼저 익히고 넘어가야 함
- 근본을 건너뛰고 Next로 바로 넘어간다면 절대 좋은 프론트 개발자가 될 수 없음
- 인쇄가 컬러풀하지는 않은데 수명이 짧은 기술 서적은 이런 게 더 좋은 것 같음
- 책 가격을 낮출 수 있을 테니
- 최신 서적답게 최신 개념을 전부 탑재하고 있음: typescript, emotion, lint, prettier, storybook 등
- 컴포넌트 단위로 설명하는데 자세하고 친절함
- 특히 인상 깊었던 내용은 storybook으로 컴포넌트 단위 개발을 하는 방법
- storybook은 잠깐 스터디했었는데 storybook의 사용 목적을 잘못 알고 있었다는 걸 이 책을 보고 알았음
- 책의 단점도 있는데 모든 프로젝트마다 초기 세팅을 설명하는 부분이 친절하기도 하지만 과하다는 느낌이 있고 본문 내용이 다소 반복되는 경향이 있음 
- 초보자에게 추천하고픈 책으로 현시점에서 리액트를 처음 공부하겠다면 이 책 보면 됨
- 초보자가 책으로 공부하는 좋은 방법
- 1) 책을 보고 처음부터 끝까지 직접 코딩하며 따라 해 보기
- 2) 토이 프로젝트를 스스로 구상해서 처음부터 끝까지 만들어 보기
- 3) 이때 모르는 내용은 책을 뒤적이며 코딩하고 해결하기
- 4) 공부할 때는 절대 ChatGPT한테 물어보지 않기
<br />

**코드팩토리의 플러터 프로그래밍** ❤️❤️❤️❤️❤️
- 현시점에서 가장 적절한 플러터 도서
- 다양한 예제로 개념을 익힐 수 있음
- 다만 후반부의 최종 예제는 다소 산에 가 있는 듯한 느낌이...
- 플러터 공부하겠다면 무조건 이 책 
<br />

**그림으로 이해하는 가상화와 컨테이너** ❤️❤️
- 가상화는 서버 가상화, 네트워크 가상화로 나뉨
- aws 기준으로 서버 가상화는  ec2, 네트워크 가상화는 vpc
- 서버 스펙 증가를 스케일업, 서버 대수 늘리기를 스케일아웃, 서버 대수 줄이기를 스케일인이라고 함
- 최초의 컨테이너 가상화 기술로 애플리케이션이 지정된 디렉토리만 접근하게 하는 리눅스의 chroot 
- 이후 도커와 쿠버네티스 등장
- 컨테이너 기술에는 데이터 포함하지 않고 분리해서 관리함
- 컨테이너 하나당 어플리케이션 하나와 같은 구성으로 마이크로아키텍처에 적합
- 컨테이너 정의: 외부 영향을 받지 않고 독립된 채 운영체제에서 실행되는 프로세스
- 클래스를 기반으로 객체 인스턴스를 생성하 듯 컨테이너 이미지를 기반으로 컨테이너 생성
- 컨테이너 하나에 프로세스 하나가 기준인데 병목현상 해결에 좋은 반면 여러 컨테이너를 실행해야 해서 관리가 복잡
- 그래서 컨테이너 오케스트레이션 필요
- 사실상 표준인 쿠버네티스가 그 역할을 함
- 책 인쇄가 크게 잘못됐음
- 4.10 ~ 4.12까지 8장 정도가 반복되어 인쇄되어 있음
- 이해를 쉽게 한다는 목적으로 양을 크게 줄이고 그림 위주로 가벼운 기획의 책인데 오히려 여러 가지가 생략되어 이해를 어렵게 만듦
<br />

**클린 코드** ❤️❤️
- 이 바닥에서 이름난 책이라 내용은 좋음
- 코드 설명하는 부분은 번역의 문제인지 자바를 안 해서인지 이해하기 어려움
- 클린 코드, 클린 아키텍처 둘 다 가독성이 좋은 책은 아니라고 봄
- 쉽고 이해하기 좋은 책도 있는 걸 보면
- 유명한 책이라고 내게도 좋은 책은 아님
<br />


**크래프톤 웨이** ❤️❤️❤️❤️❤️
- 기자가 쓴 책들은 대체로 잘 읽힘 
- 이 책도 가독성이 좋고 스토리가 살아있는 매우 재미있는 책으로 순식간에 읽어 치우게 됨
- 성공으로 가는 길이 결코 아름답지 않고 진창길이라는 걸 크래프톤의 얘기로 보여줌
- 창업주들의 얘기가 많다 보니 근로자의 입장에서 불편하게 느껴지는 내용이 많은데 그만큼 가감 없이 쓰인 책
- 직원들의 시선이 더 공감이 되기는 해도 경영진의 시선 또한 깨닫게 하는 바가 많았음 
- 재미도 있고 인사이트도 주는 좋은 책
<br />

**모두의 깃 & 깃허브** ❤️❤️❤️
- 깃을 써도 매번 똑같은 명령어만 쓰다 보니 이해도가 떨어져 한 번 정리할 목적으로 읽었음
- 책의 중간까지 소스트리라는 GUI 기반으로 설명을 해서 어이가 없었는데  또 나머지 절반은 같은 내용을 콘솔로 설명함
- 굳이 이렇게까지? 과하다 느껴지기도 하는데 초보자를 위해서라면 좋은 배려인 듯
- 단, 콘솔 부분 명령어를 다크 색상으로 하지 않아서 가독성이 떨어짐
<br />

**가상 면접 사례로 배우는 대규모 시스템 설계 기초** ❤️❤️❤️
- IT 서비스에 사용되는 시스템 설계 방법에 대해 개괄적으로 알려주는 책
- 지식 축적보다 과제를 던져주는 내용에 가까움
- 경험이 많아도 미리 고민해 보지 않았으면 짧은 시간에 대답하기 어려운 게 설계인데 그런 부분들을 미리 짚어줘서 의미 있음
- 어느 정도의 경험을 필요로 하는 책임
<br />

**쉽고 빠른 플러터 앱 개발** ❤️❤️❤️
- 장점: 쉽게 따라 하기 좋게 되어 있음
- 단점 1: 안드로이드 스튜디오가 아니라 vscode로 진행해서 초보 입장에서는 초반에 헷갈림
- 단점 2: 출간된 지 1년 정도 지났는지라 안 맞는 부분들이 조금 있음 (기술 도서 특성상 어쩔 수 없는 부분)
- 단점 3: 쉽게 접근은 가능한데 막상 다 보고 나도 겉핥기만 하고 급하게 끝내버린 느낌. 스스로 뭘 해볼 수 있겠단 생각이 안 듦   
<br />

**함수형 코딩** ❤️❤️❤️❤️❤️
- 도서관에서 빌려보다가 구매해버림
- 그만큼 좋은 책
- 구어체의 진행으로 변수 하나하나의 역할까지 친절하게 설명해 줌
- 특히 화살표로 코드를 설명하는 부분이 인상적
- 미시적인 단위에서 이렇게까지 코드를 설명해 주는 책을 본 적이 없음
- 책을 읽고 나니 껍데기를 하나 깨고 나온 느낌
- 두고두고 봐야 할 개발 도서
<br />

**소프트 스킬** ❤️❤️
- IT 서적인 줄 알았으나 그렇지는 않음
- 돈 많이 번 개발자가 말하는 인생 얘기
- 앞쪽에 개발자와 관련한 얘기도 있음
- 자기 계발서에 가까움
- 말하는 주제가 많아서 읽는데 집중하기 쉽지 않음
<br />

**러닝 타입스크립트** ❤️❤️
- 타입스크립트 책을 여러 권 읽어 봤는데 공통점이 있음
- 실무에서 실용적인 타입스크립트를 설명하는 게 아니라 타입스크립트를 위한 타입스크립트 설명을 하고 있음
- 실용 영역에서 쓸 만한 내용은 몇 줄 안 되는 것 같고 책을 만들기 위해 이것저것 복잡하게 나열하고 있는 느낌
- 예를 들면 튜플 같은거. 누가 한 배열에 string 넣고 number 넣고 boolean 넣고 쓰나? 코드리뷰때 얼마나 욕 먹으려고
- 그리고 타입스크립트 번역본들은 왜 이렇게 읽기가 힘든지
- 그나마 이 책은 핵심적인 부분들에 대한 설명만 하고 있음
- 더 복잡한 수준으로 나아가지는 않음
- 그럼에도 난독증이 있다고 느껴지게 만드는 번역체는 너무 읽기 힘듦
<br />

**소프트웨어 아키텍처 The Hard Parts** ❤️
- 소프트웨어 아키텍처 101의 후속작인데 읽기 어려움
- 내용도 어렵고 번역도 이해가 잘 안 됨
- 심화 내용이라 어려울 수는 있겠지만 읽다보면 정신이 아득해짐
- 절반 읽고 포기
<br />

**소프트웨어 아키텍처 101** ❤️❤️
- 국내에서는 개념이 생소한 아키텍트라는 직군에 대한 얘기   
- 그거 그냥 CTO나 개발 팀장이 하는 일 아닌가?   
- 외국에서는 아키텍트라는 직군이 따로 있나 봄   
- 시스템 설계, 개발팀과의 관계, 문서 작성법 등 포괄적인 내용을 담고 있음   
- 쉽지 않은 내용이고 번역투라 집중해 읽기가 힘듦   
- 여러 번 읽어봐야 머릿속에 남는 게 있을 듯 (또 읽을지는 모르겠음)   
- 아키텍트가 아니라도 개발자라면 알아야 할 내용들에 대한 책
<br />

**프론트엔드 성능 최적화 가이드** ❤️❤️❤️❤️❤
- 프론트엔드 최적화 방법은 워낙 다양하고 케바케라 정리된 책이 나올 수 있을까 했는데 욕구를 정확히 채워주는 책
- 200여 쪽으로 얇지도 두껍지도 않은데 내용도 크게 어렵지 않아 쉽게 읽을 수 있음
- 다양한 주제와 방법에 대해 얘기하는데 전혀 과하지 않음
- 바이블처럼 곁에 두고 계속 봐야 하는 책
- 단점: 최신 책임에도 현재 노드 버전에서 실행이 안 되고, 써드 파티 모듈도 안 되는 것이 있고, 예제와 책의 포트가 다르다거나, 코드 끝에 세미 콜론은 안 붙인다거나, 이젠 거의 표준처럼 자리잡은 타입 스크립트 기반이 아니라거나
- 내용은 좋은데 코드 따라하려면 안 되는 부분들이 제법 있음
<br />

**유난한 도전** ❤️❤️❤️
- 토스의 시작부터 현재까지의 얘기   
- 장점   
- 초기 스타트업이 좌충우돌하는 얘기가 재미있음   
- 시작부터 현재까지의 시간 순서대로 이야기라 스타트업 종사자들에게도 도움 됨   
- 단점
- 자화자찬이 심하고 변명 같은 얘기가 많음
- 초중반까지는 재미있는데 증권, 은행 등 다 큰 후의 얘기는 지루함
- 내부자가 써서 비판적인 시각이 부족해 균형을 잃음
- 토스 사람들이 시간 지나서 읽으면 엄청 오글거릴 듯
<br />

**프로그래머의 뇌** ❤️
- 뇌를 장기 기억 저장소, 단기 기억 저장소, 작업 기억 공간으로 구분해  설명함
- 세 부분이 조화로워야 한다고 함
- 초반에는 공감하며 읽었지만 중후반부로 갈수록 와닿지가 않아 스킵함
<br />

**따라하며 배우는 AWS 네트워크 입문** ❤️❤️
- 많고 많은 aws 항목 중에서 네트워크만 따로 빼 놓은 책
- 책 편집이 보기 좋고 따라하기 좋게 되어있지 않음
- 편집이 별로임
- 이 책 한 권 말고 다른 aws 서적과 병행해서 본다면 도움됨
<br />

**이게 무슨 일이야** ❤️❤️
- 책의 분위기와는 다르게 무거운 책
- 쉽게 읽히는 내용들은 아니었음
- 책 편집도 다소 이상함
<br />

**아마존 웹서비스(AWS Discovery book)** ❤️❤️
- 가장 많이 쓰이는 서비스를 소개함
- 기본적인 설명과 설정법
- aws를 전혀 모르는 쌩초보에게는 도움이 될 듯
<br />

**구글 엔지니어는 이렇게 일한다** ❤️❤️
- 책이 엄청 두꺼움 (600페이지 넘음)
- 구글에서 일하는 방식에 대해 씀
- 코드리뷰, 테스트, 빌드, 팀웍 등등
- 읽을수록 지침
- 간결하지가 않고 장황해서 머리에 잘 들어오지 않음
- 구글의 일하는 방식을 전부 기술한다는게 가능해 보이지 않는데 그걸 시도함
- 절반 넘게 읽다가 낙오함
<br />

**이펙티브 엔지니어** ❤️❤️❤️❤️
- 재미없음
- 그러나 개발자에게 도움되는 책
- 그래서 완독함
- 레버리지 얘기가 메인임
- 레버리지가 높은 일을 해라
- 내가 지금 한 일이 나중에 더 큰 보상으로 오는 일을 하라는 의미
- 좋은 내용을 가득 담고 있는 책   
<br />

**UX 디자이너로 일하고 있습니다** ❤️
- UX 지식을 얻으려고 골랐음
- 그러나 UX 디자이너, 직업군에 대한 얘기지 UX 지식을 말하는 책이 아님
- 내가 원하던 방향의 책이 아니었음
<br />

**사용자의 마음을 움직이는 UX 디자인의 힘** ❤️
- 3번과 마찬가지로 UX 지식을 얻으려고 골랐음
- 내용은 저자 개인적인 부분과 직업군에 대하 얘기임
- 원하던 방향의 책이 아님
<br />

**개발자의 디자인 독해력** ❤️❤️❤️❤️
- 어려운 디자인 이론으로 가득찬 책이 아님
- 쉽게 이해하고 읽을 수 있게 엮은 책
- 내용도 알차고 도움도 되서 이례적으로 두 번 읽음
- 엄청난 깊이를 원하면 다른 책을 봐야함
<br />

**클린 아키텍처** ❤️❤️
- 모두가 추천하는 바이블 같은 책
- 그러나 두 세번 읽어봐도 어렵기만 함
- 초반부는 읽을만한데 후반부로 갈 수로 무슨 얘기를 하는 건지 알아먹질 못하겠음
- 눈은 읽는데 머리에는 안 들어옴
- 번역이 문제인지 내 지능이 문제인지
<br />

**모던 자바스크립트 Deep Dive** ❤️❤️❤️❤️❤️
- 자바스크립트 개발자 필독서
- 책은 두껍지만 많이 어렵지는 않음
- 두 세번 정독하면 자바스크립트 코딩에 대한 자신감이 올라감
- 두고두고 정독해야 하는 책
<br />

**나는 LINE 개발자입니다** ❤️❤️❤️
- '네카라쿠배당토'에서 카카오 다음
- 대학으로 치면 연대, 고대쯤 되는 라인
- 잘 하는 사람들의 얘기가 많음
- 개발자들에게 많은 자극을 주는 책
<br />

**나는 아마존에서 미래를 다녔다** ❤️❤️❤️❤️
- 아마존 개발자 출신의 글
- 솔직함 그리고 놀라움
- 아마존이라는 기업, 그 안에서 일하는 구성원들이 대단하다 느껴짐
- 개발자로서 직장인으로서 배워야 할 내용들이 많음
- 일독을 권하고픈 책
<br />

**백엔드를 위한 django rest framework with 파이썬** ❤️❤️❤️❤️
- django를 위한 최신 책이 거의 없는데 22년 5월에 나온 따끈따끈한 책
- 트렌드에 맞게 backEnd django rest framework를 위한 책임
- 쌩초보를 겨냥한 책
- 중급자 이상이라도 정리할 목적으로 읽어보면 나쁘지 않을듯
- 두껍지 않아 완독하는데 얼마 걸리지 않음
- 목적과 방향성이 뚜렷해서 좋은 책
<br />

**타입스크립트 프로그래밍** ❤️
- 책이 어려움
- 번역의 문제인지 원작의 문제인지
- 두 번 시도했지만 결국 이해하지 못함
<br />

**You Don't Know JS** ❤️❤️❤️
- 두 권짜리
- 다소 오래됨
- 당연히 최신 ecma script 내용은 반영하지 못함
- 그러나 자바스크립트 근본 개념 자체가 변한건 아니기에 읽어볼 가치가 있음
- 특히 프로토타입 관련한 개념들 설명 좋음
<br />

**개발 7년차, 매니저 1일차** ❤️
- 책 편집이 정신없음
- 국내 사정과 맞지 않는 얘기들과 뻔한 얘기들
- 제목만큼 기대를 충족시켜주지 못함
<br />

**스태프 엔지니어** ❤️
- 우리나라에서는 이름도 생소한 스태프 엔지니어라는 포지션
- CTO와 팀장 사이의 어디쯤 포지션으로 보임
- 포지션도 애매한데 책 자체도 눈에 잘 안 들어옴
- 번역이 쉽게 읽히게 되진 않은 듯
- 교과서 같은 내용들이라 흥미도 안 생기고
<br />

**MongoDB 완벽가이드** ❤️❤️❤️
- mongodb 최신 메이저 버전이 6인데 이 책은 4 기준
- 가장 최근에 나온 번역본인데 아마존에서 찾아보니 출간 자체가 2019년
- 시기가 너무 늦은 책
- 그래도 mongodb 관련 서적이 많지 않고 그나마 최신이고 기본 개념에 대한 설명이 많아서 공부하려면 이 책으로
<br />

**좋은 코드, 나쁜 코드** ❤️
- 읽다가 초반에 포기
- 번역이 문제인지 잘 안 읽힘
<br />

**Building Secure & Reliable Systems SRE를 위한 시스템 설계와 구축** ❤️
- 전공 서적 같은 책
- 초반에 중단
<br />

**리팩토링** ❤️❤️
- 자바스크립트로 설명하는 리팩토링의 원칙과 방법에 관한 책
- 끝까지 읽지는 못했는데 이유는 번역이 잘 안 맞아서 집중해 읽기가 힘들었음
- 저자의 코딩 스타일도 안 맞음
- 다수에게 추천을 받은 책이지만 그렇다고 꼭 좋은 책이라는 법은 없으니 적당한 시점에 손 놓는 것도 책을 많이 읽을 수 있는 좋은 방법
<br />

**마이크로 서비스 아키텍처 구축 가이드** ❤️
- 교과서 같이 내용이 딱딱함
- 읽기 힘듦
- 사례 위주로 내용을 풀었다면 훨씬 재미있었을텐데
<br />

**개발자 원칙** ❤️
- 소위 연예인 개발자들의 하고픈 얘기 모음
- 저자별로 챕터가 나뉘어 있는데 하려는 얘기가 제각각이라 다양성이 있기보다 가독성과 난이도가 제각각임
- 타깃 독자를 개발자 전체로 뭉뚱그려서 포지셔닝 했음
- 그래서 재미도 얻는 것도 많지 않았음
- 추천한다면 이유는 다양한 얘기를 들어볼 수 있다는 것
- 추천하지 않는다면 이유는 하려는 얘기가 너무 많아 독자에게 전달되지 않기 때문에
<br />

**나는 네이버 프런트엔드 개발자입니다** ❤️
- 재미있었던 내용
- 미국 IT 회사는 일을 찾아 하지 않으면 누구도 일을 안 준다고 함
- 그만큼 성과 위주이고 그래서 해고도 자연스러움
- 미국 개발자는 두 가지 테크에 대한 선택권이 주어지는데 사람을 관리하는 매니저 테크, 개발만 하는 엔지니어 테크
- 책을 다 읽지는 않음
- 계속 읽어야 할 필요성을 못 찾음
- 개인이 알아서 쓴 책이라 내용의 질이 들쭉날쭉함
- 전반적으로 가이드라인과 주제를 정해서 책을 만들어야 함
- 안 그러면 이런 유의 책은 가치가 많이 떨어짐



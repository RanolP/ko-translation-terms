# ko-translation-terms

더 나은 번역을 위한 번역 용례집입니다.

- *기울여* 표기한 단어는 음차한 단어입니다. 가능하다면 음차하지 않은 단어를 쓸 수 있다면 좋겠습니다.
- 마땅한 번역어가 없는 단어 역시 표에는 같이 실려 있습니다. 한국어의 특성상 앞말의 받침 유무를 기준으로 조사를 가르게 되는데, 이 경우 조사 선택에 도움이 될 수 있기 때문입니다.
- 번역어는 가장 유명한 것부터 적으려고 노력하고는 있습니다. 하지만 유명성을 따로 정량적 방법 같은 걸로 재어 보지는 않았기에 별로 유명하지 않은 단어가 앞에 있을 수도 있습니다.
- <sup>{링크}</sup>가 붙은 단어는 국립국어원 기준에 부합하게 음차되었다는 뜻입니다. 그 근거는 {링크}에서 찾아보실 수 있습니다.
- \#이 뒤에 붙은 단어는 범용적으로 사용되지는 않는다는 표시입니다. 여기서 범용적이라는 말은 1) 누구나 사용한다. 2) 어디에든 사용한다. 의 두 의미 중 하나거나, 둘 다입니다.
- 단어의 순서는 사전순 정렬을 시도하고 있습니다. 눈으로 보고 하기 때문에 틀린 게 보일 수도 있습니다.
- Wikipedia의 Glossary of computer science 문서에서 일부 골라내 번역어를 덧붙였습니다. (현재 A부터 G까지 1차적으로 덧붙임, H부터 재개 필요)

## 목차

- [ko-translation-terms](#ko-translation-terms)
  - [목차](#목차)
  - [Git](#git)
  - [Rust](#rust)
  - [사이버 보안](#사이버-보안)
  - [수학](#수학)
  - [알고리즘](#알고리즘)
  - [인공지능](#인공지능)
  - [일반](#일반)
  - [파일 시스템](#파일-시스템)
  - [통신](#통신)
  - [프로그래밍 일반](#프로그래밍-일반)
  - [외부 링크](#외부-링크)

## Git

| 원어          | 음차            | 번역어          |
| ------------- | --------------- | --------------- |
| Branch        | *브랜치*        | 가지#, 가지치다 |
| Commit        | *커밋*          |                 |
| History       | *히스토리*      | 역사            |
| Merge Request | *머지 리퀘스트* | 병합 요청       |
| Repository    | *레포지토리*    | 저장소          |

## Rust

| 원어                 | 음차                   | 번역어                                            |
| -------------------- | ---------------------- | ------------------------------------------------- |
| Non-Lexical Lifetime | *논 렉시컬 라이프타임* | 괄호구역 독립적 수명#/이름 접근 범위와 다른 수명# |

## 사이버 보안

| 원어                | 음차                 | 번역어          |
| ------------------- | -------------------- | --------------- |
| Decrypt             | *디크립트*           | 복호화하다      |
| Encrypt             | *인크립트*           | 암호화하다      |
| Permission          | *퍼미션*             | 권한            |
| Private Key         | *프라이빗 키*        | 비밀 키/개인 키 |
| Public Key          | *퍼블릭 키*          | 공개 키         |
| Security            | *시큐리티*           | 보안            |
| Supply Chain Attack | *서플라이 체인 어택* | 공급망 공격     |
| Threat              | *스렛*               | 위협            |

## 수학

| 원어             | 음차               | 번역어        |
| ---------------- | ------------------ | ------------- |
| Algebra          | *알지브라*         | 대수학        |
| Algebraic        | *알지브레익*       | 대수적        |
| Boolean Algebra  | *불리언 알지브라*  | 부울 대수     |
| Category         | *카테고리*         | 범주          |
| Game Theory      | *게임 띠오리*      | 게임 이론     |
| Geometry         | *지오메트리*       | 기하학        |
| Linear Algebra   | *리니어 알지브라*  | 선형 대수학   |
| Naive Set Theory | *나이브 셋 띠오리* | 소박한 집합론 |
| Prime Number     | *프라임 넘버*      | 소수          |
| Set              | *셋*               | 집합          |

## 알고리즘

| 원어                      | 음차                     | 번역어                        |
| ------------------------- | ------------------------ | ----------------------------- |
| Binary Search             | *바이너리 서치*          | 이진 탐색/이분 탐색/이진 검색 |
| Binary Search Tree        | *바이너리 서치 트리*     | 이진 탐색 트리                |
| Binary Tree               | *바이너리 트리*          | 이진 트리                     |
| Breadth-First Search[DFS] | *브레드스 퍼스트 서치*   | 너비 우선 탐색                |
| Bruteforce                | *브루트포스*             | 무차별 대입                   |
| Bubble Sort               | *버블 소트*              | 거품 정렬                     |
| Complete Binary Tree      | *컴플리트 바이너리 트리* | 완전 이진 트리                |
| Data Structure            | *데이터 스트럭쳐*        | 자료 구조                     |
| Depth-First Search[DFS]   | *뎁스 퍼스트 서치*       | 깊이 우선 탐색                |
| Divide and Conquer        | *디바이드 앤드 컨커*     | 분할 정복                     |
| Dynamic Programming[DP]   | *다이나믹 프로그래밍*    | 동적 계획법/기억하며 풀기#    |
| Full Binary Tree          | *풀 바이너리 트리*       | 전 이진 트리                  |
| Graph                     | *그래프*                 |                               |
| Greedy                    | *그리디*                 | 탐욕법/욕심쟁이               |
| Hash Set                  | *해시셋*                 | 해시를 이용한 집합#           |
| Insertion Sort            | *인서션 소트*            | 삽입 정렬                     |
| Linked List               | *링크드 리스트*          | 연결 리스트                   |
| Merge Sort                | *머지 소트*              | 병합 정렬                     |
| Perfect Binary Tree       | *퍼펙트 바이너리 트리*   | 포화 이진 트리                |
| Segment Tree              | *세그먼트 트리*          |                               |
| Selection Sort            | *셀렉션 소트*            | 선택 정렬                     |
| Sort                      | *소트*                   | 정렬                          |
| Space Complexity          | *스페이스 컴플렉시티*    | 공간 복잡도                   |
| Time Complexity           | *타임 컴플렉시티*        | 시간 복잡도                   |
| Tree                      | *트리*                   | 수형도/나무#                  |

## 인공지능

| 원어                        | 음차                  | 번역어    |
| --------------------------- | --------------------- | --------- |
| Artificial Intelligence[AI] | *아티피셜 인텔리전스* | 인공지능  |
| Corpus                      | *코퍼스*              | 말뭉치    |
| Machine Learning[ML]        | *머신 러닝*           | 기계 학습 |
| Training                    | *트레이닝*            | 훈련      |
| Transfer Learning           | *트랜스퍼 러닝*       | 전이 학습 |

## 일반

| 원어          | 음차              | 번역어                       |
| ------------- | ----------------- | ---------------------------- |
| Best Practice | *베스트 프랙티스* | 모범 사례                    |
| Download      | *다운로드*        | 내려받다                     |
| Entropy       | *엔트로피*        | 무질서도                     |
| External      | *익스터널*        | 외부(의)                     |
| Guide         | *가이드*          | 안내서/입문서, 안내자/안내원 |
| Notification  | *노티피케이션*    | 알림                         |
| Superscript   | *슈퍼스크립트*    | 위 첨자/어깨번호#            |
| Subscript     | *서브스크립트*    | 아래 첨자/무릎번호#          |
| Tutorial      | *튜토리얼*        | 자습서/지도서/입문서         |
| Upload        | *업로드*          | 올려주다/올리다              |

## 파일 시스템

| 원어               | 음차                                                                                               | 번역어      |
| ------------------ | -------------------------------------------------------------------------------------------------- | ----------- |
| Directory          | *디렉터리*<sup>[온라인가나다 상세보기(디렉토리//디렉터리 어느 것이 맞습니까?)][]</sup>, *디렉토리* |             |
| File               | *파일*                                                                                             |             |
| Filename Extension | *파일네임 익스텐션*                                                                                | 파일 확장자 |
| Path               | *패스*                                                                                             | 경로        |

## 통신

| 원어                 | 음차                  | 번역어 |
| -------------------- | --------------------- | ------ |
| Transmission Network | *트랜스미션 네트워크* | 통신망 |

## 프로그래밍 일반

| 원어                                   | 음차                                                                       | 번역어                                                          |
| -------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Abstract(ion)                          | *앱스트랙트*/*앱스트랙션*                                                  | 추상(화)                                                        |
| Abstract Data Type[ADT]                | *앱스트랙트 데이터 타입*                                                   | 추상 자료형/추상 데이터 타입                                    |
| Allocation                             | *얼로케이션*                                                               | 할당                                                            |
| Annotation                             | *어노테이션*                                                               | 주석                                                            |
| Application                            | *애플리케이션*/*앱*                                                        | 응용 프로그램/앱                                                |
| Application Programming Interface[API] | *애플리케이션 프로그래밍 인터페이스*                                       |                                                                 |
| Array                                  | *어레이*                                                                   | 배열                                                            |
| Architecture                           | *아키텍처*                                                                 | 설계#                                                           |
| Archive                                | *아카이브*                                                                 |                                                                 |
| ASCII                                  | *아스키*                                                                   |                                                                 |
| Assert                                 | *어서트*                                                                   | 단언                                                            |
| Assignment                             | *어사인먼트*                                                               | 대입/할당                                                       |
| Associative Array                      | *어소시에이티브 어레이*                                                    | 연관 배열                                                       |
| Asynchronous                           | *어싱크로노스*                                                             | 비동기                                                          |
| Attribute                              | *어트리뷰트*                                                               | 속성/특성                                                       |
| Automata                               | *오토마타*                                                                 |                                                                 |
| Automatic Memory Management            | *오토매틱 메모리 매니지먼트*                                               | 자동 메모리 관리                                                |
| Bandwidth                              | *밴드위스*                                                                 | 대역폭                                                          |
| Booting                                | *부팅*                                                                     | 시동#                                                           |
| Borrow                                 | *바로우*                                                                   | 빌리다                                                          |
| Breaking Change                        | *브레이킹 체인지*                                                          | 단절적 변경#                                                    |
| Byte                                   | *바이트*                                                                   |                                                                 |
| Callback                               | *콜백*                                                                     |                                                                 |
| Central Processing Unit[CPU]           | *센트럴 프로세싱 유닛*                                                     | 중앙 처리 장치                                                  |
| Class                                  | *클래스*                                                                   |                                                                 |
| Closure                                | *클로저*                                                                   |                                                                 |
| Command                                | *커맨드*                                                                   | 명령/명령어                                                     |
| Comment                                | *코멘트*                                                                   | 주석                                                            |
| Compiler                               | *컴파일러*                                                                 |                                                                 |
| Component                              | *컴포넌트*                                                                 | 구성 요소#                                                      |
| Compress(ion)                          | *컴프레스*/*컴프레션*                                                      | 압축(하다)                                                      |
| Computability Theory                   | *컴퓨터빌리티 띠오리*                                                      | 계산 가능성 이론                                                |
| Computation                            | *컴퓨테이션*                                                               | 계산                                                            |
| Computer                               | *컴퓨터*                                                                   | 셈틀#                                                           |
| Computer Architecture                  | *컴퓨터 아키텍처*                                                          | 컴퓨터 구조                                                     |
| Computer Graphics                      | *컴퓨터 그래픽스*                                                          |                                                                 |
| Concatenation                          | *컨케트네이션*                                                             | 연결/접합                                                       |
| Concurrency                            | *컨커런시*                                                                 | 동시성                                                          |
| Conditional                            | *컨디셔널*                                                                 | 조건적                                                          |
| Configuration                          | *컨피규레이션*                                                             | 설정                                                            |
| Conflict                               | *컨플릭트*                                                                 | 충돌                                                            |
| Console                                | *콘솔*                                                                     |                                                                 |
| Continuation                           | *컨티뉴에이션*                                                             | 후속문                                                          |
| Control Flow                           | *컨트롤 플로*                                                              | 흐름 제어                                                       |
| Control Panel                          | *컨트롤 패널*                                                              | 제어판                                                          |
| Copy                                   | *카피*                                                                     | 복사                                                            |
| Declaration                            | *데클러레이션*                                                             | 선언                                                            |
| Dependency                             | *디펜던시*                                                                 | 의존성/종속성                                                   |
| Deserialization                        | *디시리얼라이제이션*                                                       | 역직렬화                                                        |
| Documentation                          | *도큐멘테이션*                                                             | 문서                                                            |
| Domain                                 | *도메인*                                                                   | 문제 영역                                                       |
| Double Precision                       | *더블 프리시전*                                                            | 배정밀도                                                        |
| Error                                  | *에러*                                                                     | 오류                                                            |
| Event-Driven Programming               | *이벤트 드리븐 프로그래밍*                                                 | 사건 기반 프로그래밍                                            |
| Exception                              | *익셉션*                                                                   | 예외                                                            |
| Executable                             | *익스큐터블*                                                               | 실행 가능한                                                     |
| Expression                             | *익스프레션*                                                               | 표현식/식                                                       |
| Extension                              | *익스텐션*                                                                 | 확장                                                            |
| Fault Tolerance                        | *폴트 톨러런스*                                                            | 장애 허용/결함 허용                                             |
| Field                                  | *필드*                                                                     | 입력란                                                          |
| Floating Point Arithmetic              | *플로팅 포인트 아리스메틱*                                                 | 부동 소수점 연산/둥둥 소수점 연산#                              |
| Foreign Function Interface[FFI]        | *포레인 펑션 인터페이스*                                                   | 외부 함수 인터페이스                                            |
| Fragmentation                          | *프래그먼테이션*                                                           | 단편화                                                          |
| Framework                              | *프레임워크*                                                               |                                                                 |
| Function                               | *펑션*                                                                     | 함수                                                            |
| Garbage Collection[GC]                 | *가비지 콜렉션*                                                            | 쓰레기 수집/쓰레기 수거                                         |
| Global Variable                        | *글로벌 버라이어블*                                                        | 전역 변수                                                       |
| Globalization[g11n]                    | *글로벌라이제이션*                                                         | 세계화                                                          |
| Inheritance                            | *인헤리턴스*                                                               | 상속                                                            |
| Inject(ion)                            | *인젝트*/*인젝션*                                                          | 주입(하다)                                                      |
| Inter Process Communication[IPC]       | *인터 프로세스 커뮤니케이션*                                               | 프로세스 간 통신                                                |
| Intercept                              | *인터셉트*                                                                 | 가로채다                                                        |
| Internationalization[i18n]             | *인터내셔널라이제이션*                                                     | 국제화                                                          |
| Key                                    | *키*                                                                       | 글쇠                                                            |
| Keyboard                               | *키보드*                                                                   | 자판/글쇠판#                                                    |
| Keyword                                | *키워드*                                                                   | 핵심어                                                          |
| Lazy                                   | *레이지*                                                                   | (계산을) 미루는                                                 |
| Library                                | *라이브러리*                                                               |                                                                 |
| Lifecycle                              | *라이프사이클*                                                             | 생애주기/생명주기                                               |
| Lifetime                               | *라이프타임*                                                               | 수명/생존 기간/생존 범위                                        |
| Localization[l10n]                     | *로컬라이제이션*                                                           | 지역화                                                          |
| Memory Alignment                       | *메모리 얼라인먼트*                                                        | 메모리 정렬                                                     |
| Merge                                  | *머지*                                                                     | 병합                                                            |
| Message                                | *메시지*<sup>[온라인가나다 상세보기('메시지'와 '메세지')][]</sup>, 메세지  |                                                                 |
| Method                                 | *메서드*                                                                   |                                                                 |
| Minifying                              | *미니파잉*                                                                 | 경량화                                                          |
| Module                                 | *모듈*                                                                     |                                                                 |
| Namespace                              | *네임스페이스*                                                             | 이름 공간                                                       |
| Object                                 | *오브젝트*                                                                 | 객체                                                            |
| Operating System[OS]                   | *오퍼레이팅 시스템*                                                        | 운영 체제                                                       |
| Ownership                              | *오너십*                                                                   | 소유권                                                          |
| Package                                | *패키지*                                                                   | 꾸러미#                                                         |
| Polymorphism                           | *폴리모피즘*                                                               | 다형성                                                          |
| Pre-                                   | *프리*                                                                     | 사전/미리                                                       |
| Prior Art                              | *프라이오 아트*                                                            | 선행 기술                                                       |
| Procedure                              | *프로시저*                                                                 |                                                                 |
| Property                               | *프로퍼티*                                                                 | 속성                                                            |
| Reference                              | *레퍼런스*                                                                 | 참조, 참고 문서                                                 |
| Reference Counting                     | *레퍼런스 카운팅*                                                          | 참조 세기 (기법)                                                |
| Regression                             | *리그레션*                                                                 | 회귀, [퇴보](https://en.wikipedia.org/wiki/Software_regression) |
| Regular Expression[Regex]              | *레귤러 익스프레션*/*[레리][겍긱젝직]스*                                   | 정규 표현식/정규식                                              |
| Request                                | *리퀘스트*                                                                 | 요청                                                            |
| Response                               | *리스폰스*                                                                 | 응답                                                            |
| Routine                                | *루틴*                                                                     |                                                                 |
| Semanting Versioning                   | *시맨틱 버저닝*                                                            | 유의적 버전                                                     |
| Serialization                          | *시리얼라이제이션*                                                         | 직렬화                                                          |
| Setting                                | *세팅*                                                                     | 설정                                                            |
| Shell                                  | *셸*<sup>[온라인가나다 상세보기(shell은 쉘인가요 셸인가요?)][]</sup>, *쉘* |                                                                 |
| State of the Art[SOTA]                 | *스테이트 오브 더 아트*                                                    | 최첨단                                                          |
| Statement                              | *스테이트먼트*                                                             | 구문/문                                                         |
| Terminal                               | *터미널*                                                                   | 단말#                                                           |
| Tool                                   | *툴*                                                                       | 도구                                                            |
| Third Party                            | *서드 파티*                                                                | 제삼자/타사                                                     |
| Working Group                          | *워킹 그룹*                                                                | 작업 그룹/작업반                                                |

## 외부 링크

- [수학용어한영번역 - 대한수학회](https://www.kms.or.kr/mathdict/list.html)
- [번역용례 - 이광근 교수 외](http://kwangkeunyi.snu.ac.kr/lib/term/)
- [영어-한글 표기 변환기 Alpha -  muik (2016)](https://transliterator.herokuapp.com/)
- [한국어 어문 규범 용례 찾기 - 국립국어원](https://kornorms.korean.go.kr//example/exampleList.do)
- [Webpack 문서 한국어 번역 용어집 - LINE](https://github.com/line/webpack.kr/wiki/Glossary)
- [KERAS 공식 문서 한국어판 용어 통일안 - KERAS Team](https://github.com/keras-team/keras-docs-ko#%EC%9A%A9%EC%96%B4-%ED%86%B5%EC%9D%BC%EC%95%88)
- [정보통신용어사전 - 한국정보통신기술협회](http://word.tta.or.kr/main.do)
- [KS 표준용어사전 - 국가기술표준원](https://standard.go.kr/KSCI/dictionary/getDictionaryList.do)
- [MDN 번역 콘텐츠 용어 지침 - MDN](https://github.com/mdn/translated-content/blob/main/docs/ko/translation-guide.md#%EC%9A%A9%EC%96%B4-%EC%A7%80%EC%B9%A8)
- [Glossary of Computer Science - Wikipedia](https://en.wikipedia.org/wiki/Glossary_of_computer_science)

[온라인가나다 상세보기(shell은 쉘인가요 셸인가요?)]: https://www.korean.go.kr/front/onlineQna/onlineQnaView.do?mn_id=&qna_seq=227009&pageIndex=1
[온라인가나다 상세보기(디렉토리//디렉터리 어느 것이 맞습니까?)]: https://www.korean.go.kr/front/onlineQna/onlineQnaView.do?mn_id=216&qna_seq=50452
[온라인가나다 상세보기('메시지'와 '메세지')]: https://www.korean.go.kr/front/onlineQna/onlineQnaView.do?mn_id=216&qna_seq=121468

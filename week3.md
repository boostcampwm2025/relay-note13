# ✔️토론하기

### 유지점

1번(AI 프로젝트 시각화 매니저): 그림을 이용해 프로젝트 구조나 학습한 내용을 시각적인 구조로 표현할 수 있다.

2번(AI 데일리 체크포인트 생성기): 본인이 작성한 체크포인트에 대해 누락, 실수, 오류 등을 점검받을 수 있다.

3번(AI 심리 상담기): AI를 통해 심리 상담 및 기분전환을 할 수 있다.

4번(AI 모의 면접관): AI를 통해 기술 면접을 준비하는 식으로 질문을 받고 대답할 수 있다.

### 개선점

1번: 초안으로 적합하나 내 의도와 맞는 그림이 완성형태로 나오기 부족하다.

리드미나 학습정리를 입력해서. 어디에 어느 시각화 자료가 들어가면 좋을 것 같은지 알려달라하면 좋을 것 같다.
직접 시각화 자료를 받는 것은 퀄리티적으로 문제가 있다.

‘어느지점에 시각자료가 들어가면 좋은지 점검’을 수행하고 해당 자리에 시각자료를 AI로 만들어 학습정리 혹은 리드미에 추가하면 좋을 것 같다

2번: 체크포인트 피드백 시 본인의 구현 상 부족한 부분을 Ai가 체크해주는 것은 좋다. 하지만, 그것이 AI가 제시한 체크포인트를 구현하는 것인지 점검할 필요는 있다.

3번: AI는 분석, 경과 모니터링 등 부수적인 일에서는 도움이 될 수 있지만 진짜 사람과 사람 사이의 심리 상담의 본질에는 한계가 명확하다고 합니다. 심리상담 AI에서 기분전환 AI로 조금 더 가볍게 퀘스트를 개선해보았습니다.

4번: 학습을 한 내용을 점검받는 방식을 "학습내용과 관련해 의도적으로 만들어진 오류를 디버깅해보면서 개념에 대해 제대로 이해한다." 로 변경한다. 예시: 컴파일 에러가 발생하는 코드를 AI에게 만들게 하고, 그 코드가 어떤 문제인지, 어떻게 해결할 수 있는지 ai에게 답변한다.

---

# ✔️ 조사하기

## 퀘스트 1
### **개선한 퀘스트 흐름**

 이전의 퀘스트 1번은 프로젝트 전체적인 다이어그램을 시각화하는 것이다. 우리가 생각한 개선 방향은 README 혹은 학습정리에서 시각화하면 좋을 부분들을 본인이 찾던지 아니면 AI가 찾아주고 부분적인 글들을 AI가 시각화 해주는 방향으로 바꿔보았다.

1. 본인이 혹은 AI를 사용하여 README, 학습정리에서 시각화하고 싶은 포인트를 찾는다.
2. Canva, Claude 등 AI를 이용하여 시각화 도움을 받는다.

### 개선한 퀘스트가 가능한지 시연해보기

**AI를 사용해 시각화 포인트 추천받기**

학습정리를 모두 긁어 Chat GPT에게 입력했다. 아래는 프롬프트이다.

```
//... 학습정리 생략...

 Git의 blob은 얕은 복사와 유사하다. Git은 파일의 내용을 저장할 때 내용과 헤더를 기반으로 SHA1 해시를 계산하여 주소를 만든다. 두 개의 파일이 내용이 같으면 하나의 blob 객체를 참조한다. 내용을 기준으로 동일한 해시 주소를 공유하기 때문에 결과적으로 하나의 blob 객체를 참조하는 꼴이 되는 것이다. 이를통해 Git은 저장 용량을 효율적으로 관리할 수 있다. << 내 학습정리야 어느 부분을 시각화해서 나타내면 독자들이 읽는데 이해가 쉬울까 ? 시각화 하지말고, 시각화하면 좋을 포인트를 몇 개 집어줘. 이때, 내 학습정리에서 어떤 글인지 정확히 출력해서 내게 보내줘. 시각화도구는 다른 도구를 사용할 거기 때문에 시각화할 필요는 없어.  
```

GPT 응답을 보고 1번 git add명령어의 흐름을 시각화 하기로 했다.

<img width="472" height="714" alt="image" src="https://github.com/user-attachments/assets/c5be77a0-7f68-4a06-b986-7b5ad00c0570" />


### Canva, Claude 등 AI를 이용하여 시각화하기

**시각화할 내용**

### git add 명령어 구현

add 명령어의 흐름입니다.

- 파일 내용을 읽는다.
- 내용으로 해시값을 만든다.
- 블롭을 생성한다.
- 파일의 변화가 없으면 인덱스에 갱신하지않는다.
- 변화가 있다면 인덱스에 갱신한다.

**사용한 프롬프트**

```
### git add 명령어 구현

add 명령어의 흐름입니다.

- 파일 내용을 읽는다.
- 내용으로 해시값을 만든다.
- 블롭을 생성한다.
- 파일의 변화가 없으면 인덱스에 갱신하지않는다.
- 변화가 있다면 인덱스에 갱신한다. << 이 절차를 이해하기 쉽게 블로그에 삽입할 그림을 만들어줘
```

**Canva 시각화 결과**

<img width="492" height="595" alt="image" src="https://github.com/user-attachments/assets/3c10473a-f5ef-4b6e-9686-1a117b8eaf53" />


시각화 AI로는 Canva를 사용했다. 이쁘게 잘 정리가 된 것을 알 수 있다. README에 삽입하면 문제 해결 과정을 잘 이해하는데 도움될 것 같다.

내용을 기반으로한 프롬프트를 Claude에게 동일하게 입력하였다. 

**Claude 시각화 결과**

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/1e512c07-2a3b-49ec-9e5d-57dfa0910ad7" />

클로드보다는 칸바가 더 깔끔하게 나온 것 같다. 이렇게 해당 퀘스트를 수행하는데 문제가 없음을 조사하였다.

## 퀘스트 3

### 자료 조사

#### A. AI가 주는 심리 상담이 과연 효과가 있을까?

1. [10 Reasons Why Psychotherapy Cannot Be Conducted by Artificial Intelligence](https://www.pcpsychservices.com/post/10-reasons-why-psychotherapy-cannot-be-conducted-by-artificial-intelligencepsychotherapy)

2. 위 자료를 보면 알 수 있듯이 이는 분석, 감정 모니터링 등 부수적인 일에서는 도움이 될 수 있지만
   진짜 사람과 사람 사이의 심리 상담의 본질에는 한계가 명확하다고 합니다.

---

## 퀘스트 4

[퀘스트 4번 자료](https://www.themoonlight.io/ko/review/bugspotter-automated-generation-of-code-debugging-exercises)
위 자료에 따르면 BugSpotter가 LLM을 기반으로 생성된 오류코드가 교육자가 생성한 오류코드와 유사한 수준으로, 교육자의 부담을 덜어준다고 합니다.
AI가 오류코드를 제공함으로서 교육자의 역할을 대신할 수 있다고 생각했습니다.

---

# ✔️개선한 퀘스트

## 퀘스트 1: 📊 AI 시각화 매니저: README 혹은 학습정리에서 시각화

### 목표:

README 혹은 학습정리에서 시각화하면 좋을 부분들을 본인이 찾던지 아니면 AI가 찾아주고 부분적인 글들을 AI가 시각화한다.

### 설명:

이전의 퀘스트 1번은 프로젝트 전체적인 다이어그램을 시각화하는 것이다. 우리가 생각한 개선 방향은 README 혹은 학습정리에서 시각화하면 좋을 부분들을 본인이 찾던지 아니면 AI가 찾아주고 부분적인 글들을 AI가 시각화 해주는 방향으로 바꿔보았다.
본인이 혹은 AI를 사용하여 README, 학습정리에서 시각화하고 싶은 포인트를 찾는다.
Canva(GPT), Claude 등 AI를 이용하여 시각화 도움을 받는다.

### 성과물:

AI가 생성한 이미지 1장 이상 업로드

### 퀘스트과정:
퀘스트 수행 과정
 
 퀘스트 완료를 위한 2개의 과정이 있다.
 
 1. 본인이 혹은 AI를 사용하여 README, 학습정리에서 시각화하고 싶은 포인트를 찾는다.
 2. Canva, Claude 등 AI를 이용하여 시각화 도움을 받는다.
 
 ## **과정1) 본인, 혹은 AI를 사용해 시각화 포인트 추천받기**
 
 AI의 도움으로 시각화 포인트를 추천받거나 아니면, 본인이 시각화 하고 싶은 포인트를 정하면 된다.
 
 AI의 도움을 받을 때 어떻게 하면 될지 기술했다.
 
 학습정리를 모두 긁어 Chat GPT에게 입력했다. 아래는 프롬프트이다.
 
 ```
 //... 학습정리 생략...
 
  Git의 blob은 얕은 복사와 유사하다. Git은 파일의 내용을 저장할 때 내용과 헤더를 기반으로 SHA1 해시를 계산하여 주소를 만든다. 두 개의 파일이 내용이 같으면 하나의 blob 객체를 참조한다. 내용을 기준으로 동일한 해시 주소를 공유하기 때문에 결과적으로 하나의 blob 객체를 참조하는 꼴이 되는 것이다. 이를통해 Git은 저장 용량을 효율적으로 관리할 수 있다. << 내 학습정리야 어느 부분을 시각화해서 나타내면 독자들이 읽는데 이해가 쉬울까 ? 시각화 하지말고, 시각화하면 좋을 포인트를 몇 개 집어줘. 이때, 내 학습정리에서 어떤 글인지 정확히 출력해서 내게 보내줘. 시각화도구는 다른 도구를 사용할 거기 때문에 시각화할 필요는 없어.  
 ```
 
 예시는 GPT 응답에서 1번 git add명령어의 흐름을 시각화 하기로 했다. GPT의 응답은 **조사하기** 를 참고한다.

 
 ## 과정2) Canva, Claude 등 AI를 이용하여 시각화한다.
 
 Google에 canva ai를 검색하여 canva에 들어간다.
 
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/cd8d730a-a39f-427a-bc12-b17b316b01e0" />

 아래의 이미지생성, 문서 초안 작성, 코드 생성에서 **반드시 코드 생성**을 클릭한다.시각화할 내용을 쓰고 추가 프롬프트를 입력한다
 
 <img width="390" height="200" alt="image" src="https://github.com/user-attachments/assets/bae654e1-bf5b-4308-881b-4a4ada4041b0" />

 
 완성된 결과를 캡쳐하여 README, 학습정리에 사용한다
 
<img width="350" height="210" alt="image" src="https://github.com/user-attachments/assets/5eb0ca5c-3083-4d2d-9796-3edf0e086d21" />



## 퀘스트 2: 🎯 **AI 데일리 체크포인트 생성기**

### 목표

AI를 활용해 나만의 체크포인트를 점검하고, 학습 흐름에 필요한 중요 포인트를 발견한다.

### 설명

미션을 분석하고 직접 작성한 나만의 체크포인트를 AI에게 보내면, AI가 기술적 관점에서 체크포인트가 이상없이 이루어지기 위해 필요한 추가 내용 3-5개를 추출하고 추가 학습 포인트를 제안한다.

### 성과물:

제안 받은 추가 학습내용을 학습한 어떠한 수단과 방법이든 표현 가능함

## 퀘스트 3: 📘 AI를 사용하여 기분 전환을 해보자 !

### 목표:

미션으로 인해 지친 나를 위해 나만의 방식으로 AI를 사용하여 기분을 전환시켜보자!

### 설명

캠퍼 분들마다 다르시겠지만 “AI를 통해 심리적으로 위로를 받는 경험을 한 분들이 과연 많을까?”에 대해 의문을 가지게 되었고, 오히려 AI를 가벼운 기분전환용으로 사용하는 것이 더 효과가 좋을 것 같다는 결론에 도달했습니다. 꼭 본인만의 방식을 찾아 퀘스트를 진행해주시면 되고 예시는 하단에 작성하였습니다. 확인해주시면 감사하겠습니다!

- 주 3회 정도 퀘스트 수행을 추천드립니다.
- 슬랙에 공유하고 싶으신 분들은 자유롭게 진행해주시면 감사하겠습니다!

### 성과물:

AI가 생성한 기분전환용 콘텐츠 캡처 1장 업로드 또는 슬랙에 공유

### 예시 프롬프트

예시 프롬프트에 앞서, 저는 커피를 좋아하기 때문에 오늘 미션 내용에 엮어 어울리는 커피를 추천받아봤습니다.

```
< N일차 미션 내용을 삽입 >

오늘 미션 내용과 어울리는 커피를 추천해줘..!
```

> 실제로 프로세스와 스레드 동시성 관련한 미션 내용을 넣었더니, 정말 재미있게 잘 엮어서 답변을 주더라구요,, 궁금하시면 한 번 물어보셔도 좋을 것 같습니다!

### 퀘스트4 : 🐛 AI가 고의로 넣은 버그 찾기 챌린지

#### 목표

학습내용과 관련해 의도적으로 만들어진 오류를 디버깅해보면서 개념에 대해 제대로 이해한다.

#### 설명

AI에게 학습내용과 관련해 의도적으로 오류가 있는 코드를 작성하도록 하고, 어떤 부분이 왜 문제가 있는지 학습자가 찾아내도록 한다.
https://www.themoonlight.io/ko/review/bugspotter-automated-generation-of-code-debugging-exercises  
위 자료에 따르면 BugSpotter가 LLM을 기반으로 생성된 오류코드가 교육자가 생성한 오류코드와 유사한 수준으로, 교육자의 부담을 덜어준다고 합니다.  
AI가 오류코드를 제공함으로서 교육자의 역할을 대신할 수 있다고 생각했습니다.

> 오류 예시  
> i) 컴파일 에러가 발생하는 코드  
> ii) 컴파일은 안되지만, 동작이 이상한 코드  
> iii) 성능 문제나 메모리 누수 등이 발생하는 코드

예시프롬프트

```
오늘 해볼 활동은 'AI가 고의로 넣은 버그 찾기 챌린지'야. 내가 '오늘 학습한 내용'에 대해 말해주면, 그와 관련된 오류 코드를 고의로 만들어줘.(학습한 내용마다 1개씩)
그러면 내가 그 코드에서 문제점이 무엇인지 맞춰볼게. 너는 그에 대한 피드백을 주면 돼.
[오늘 학습한 내용]
runBlocking, launch를 이용한 비동기 프로그래밍, .git 내부 저장 구조, zlib를 활용해 .git/objects 내부의 객체를 읽어보기
[오류 예시]
i) 컴파일 에러가 발생하는 코드
ii) 컴파일은 안되지만, 동작이 이상한 코드
iii) 성능 문제나 메모리 누수 등이 발생하는 코드
```

만들어진 문제예시  
<img width="668" height="502" alt="image" src="https://github.com/user-attachments/assets/5166f49c-5a36-4aa1-8ae9-29a8613812c3" />

해설예시  
<img width="649" height="684" alt="image" src="https://github.com/user-attachments/assets/01806e2e-d701-496d-a931-2781209f9c57" />

### J041_김병훈
- 선정한 퀘스트 : 퀘스트 3. 📘 AI를 사용하여 기분 전환을 해보자 !
- 선정한 이유 : AI 이미지 생성을 최대한 활용하고 싶었다. 오늘의 기분이나 미래의 모습등 흔한 내용들을 많이 하다보니까 신선한 내용들을 접하고 싶었는데 미션과 음식을 연과짓는 예시(ex : 오늘 미션 내용과 어울리는 커피를 추천해줘..!) 를 보면서 재밌어 보여서 선정하였다.


### J291_홍신영
- 선정한 퀘스트 : 퀘스트 3. 📘 AI를 사용하여 기분 전환을 해보자 !
- 선정한 이유 : 미션을 수행하면서 코드가 잘 풀리지 않을 때, 학습 도중 이해가 잘 안 될 때 스트레스를 받기도 하고 3주째 개인 일상이 없고 네부캠만 신경쓰고 하다보니 점점 힘이 나지 않은 것 같아 그때마다 기분 전환을 AI와 해보고 싶어 선정하였습니다.

### J072
- 선정한 퀘스트: 퀘스트 2: 🎯 AI 데일리 체크포인트 생성기
- 선정한 이유: 작성한 체크포인트를 AI를 통해 이중점검하며 필요한 내용을 확실히 체크하고 과제를 해보고싶어 선정하였습니다.

### J256_조천산
- 선정한 퀘스트: 퀘스트 1: 📊 AI 시각화 매니저: README 혹은 학습정리에서 시각화
- 선정한 이유: 자신이 배운 내용을 타인에게 잘 설명하는 것도 문제해결력의 일부입니다. ai를 좀 더 다각도로 활용할 수 있는 퀘스트라고 생각해 선정했습니다.

# ✔️토론하기
### 유지점
- 미션을 통해 작성(혹은 설계)한 프로그램의 데이터 흐름 등을 시각화 하려는 시도
- 퀘스트의 간단한 요구사항

### 개선점
- `마크다운의 mermaid 엔진을 사용해 ERD 를 만들어줘` 이런 방식의 구체적인 지시가 들어갔으면 더 좋았을거 같다
- 퀘스트의 목적이나 방향이 너무 학습쪽으로 치우쳐져 있다. 육체적, 정신적 건강을 관리하는 방향도 생각해보면 좋을거같다.
- 스스로 만든 체크포인트를 넘겨주고 여기서 추가적으로 더 학습할 부분을 제안받는 방식이 더 좋아보인다.
- 회고 코칭 시, 좋은 점만 받기보다는 객관적으로 안좋은 점도 같이 피드백 받기

# ✔️개선한 퀘스트
### 퀘스트 1: 📊 AI 프로젝트 시각화 매니저(개선버전: 예제 프롬프트 추가)
- 목표: AI를 활용해 프로젝트에 필요한 기술 다이어그램을 생성하고 문서화를 개선한다.
- 설명: 프로젝트의 아키텍처, 데이터 흐름, API 구조 등을 AI에게 설명하면, AI가 시스템 아키텍처 다이어그램, 플로우차트, ERD, 시퀀스 다이어그램 등 프로젝트에 필요한 기술 문서용 다이어그램을 생성한다.
- 예제 프롬프트: (앞에는 스스로 작성한 코드 첨부) 내가 작성한 프로그램의 구조를 보고 프로그램의 데이터 흐름을 마크다운의 mermaid 엔진을 사용해 (다이어그램, ERD, 플로우 차트 중 퀘스트 진행자가 원하는거 택1) 으로 표현해줘
- 성과물: AI가 생성한 프로젝트 관련 다이어그램 1개와 사용 목적 설명 캡처 1장 업로드

### 퀘스트 2: 🎯 AI 데일리 체크포인트 점검기 (개선버전)
- 목표: AI를 활용해 나만의 체크포인트를 점검하고, 학습 흐름에 필요한 중요 포인트를 발견한다.
- 설명: 미션을 분석하고 직접 작성한 나만의 체크포인트를  AI에게 보내면, AI가 기술적 관점에서 체크포인트가 이상없이 이루어지기 위해 필요한 추가 내용 3-5개를 추출하고 추가 학습 포인트를 제안한다.
- 성과물: 제안 받은 추가 학습내용을 학습한 어떠한 수단과 방법이든 표현 가능함

### 퀘스트 3: 📘 AI 심리 상담기
- 목표: 지속가능한 성장을 위해 AI를 활용해 심리 상담을 받아본다.
- 설명: 오늘 하루 배웠던 점과 힘들었던 점을 적으면서 위로를 받아본다.
- 성과물: 인상 깊은 위로의 말을 캡쳐해서 올리고, 느낀 점을 적어보자.

### 퀘스트 4 :💼 AI 모의 면접관
- 목표: AI를 활용해 기술 면접을 준비하고, 스스로의 이해도를 점검한다.
- 설명: 작성한 README.md나 학습 정리.md AI에게 제공하면, AI가 실무 면접관 관점에서 기술에 대한 질문,기술의 원리에 대한 질문, 기술의 응용에 대한 질문 3개와 각각의 꼬리 질문을 생성하고, 이에 대해 AI 도움 없이 답변을 작성한다. 그 후 그 답변에 대한 피드백을 받는다
- 성과물: AI가 생성한 질문 목록, AI 피드백과 본인 답변이 포함된 캡처 1장 업로드




### J011\_강용현 - 🎯 AI 데일리 체크포인트 점검기 (개선버전)

`선택한 이유`
직접 작성한 체크 포인트에는 러프하게 작성하다 보니 빠진 부분들이 많다. 빠진 부분들을 AI를 통해 분석하면서 내가 체크 하지 못하는 부분들을 체크하고 그런 부분들이 어딘지 파악해볼수 있을것 같다.

**`수행 결과`**
<img width="912" height="880" alt="image" src="https://private-user-images.githubusercontent.com/154689763/473284152-d59fdb59-e49d-4fa0-a677-24a43c9dec2d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTQwMjIyNDIsIm5iZiI6MTc1NDAyMTk0MiwicGF0aCI6Ii8xNTQ2ODk3NjMvNDczMjg0MTUyLWQ1OWZkYjU5LWU0OWQtNGZhMC1hNjc3LTI0YTQzYzlkZWMyZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwODAxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDgwMVQwNDE5MDJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yNDY0MTU0YzYxYjVlOTkxOTc4Y2FlMTJlZDIwNTc2YzdkNjg5YmM2NmM1NTg4ZWY5YmMwNmMwYzI5NjVkYjQ0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.M_IG6AaVRzhoctaA9nR-FJ_qXiuAHrdhzOmwBrq4tqw" />
</details>

**`느낀점`**

구현에 집중해서 신경 쓰지 못한 학습 포인트를 AI가 짚어주면서 학습을 좀 더 깊게 할 수 있었던 것 같다. 학습 이후에도 추가적으로 AI에게 추천을 받아 학습을 진행해보고자 한다

### J143\_송상화 - 📊 AI 프로젝트 시각화 매니저(개선버전: 예제 프롬프트 추가)

문서 작성 시 다이어그램을 첨부하면 이해에 많은 도움이 되는 것 같아 이번 기회에 mermaid 로 다이어그램을 만들어 보기로 결정했다.

<details>
<summary>부스트 영상 서비스</summary>

#### 내용

결과를 출력하기 위한 최종 인터페이스가 담겨 있는 use case 를 바탕으로 다이어그램을 만들어 달라고 부탁했다.

디테일한 필드나 메서드는 조금 수정했다.

#### 프롬프트

```
import Publisher from './Publisher.js';
import Broker from './Broker.js';
import Video from './Video.js';
import { Uploader, Converter, Validator } from './VideoModule.js';

// ================ Message Broker ================ // 

const broker = new Broker();

// ================ Video Modules ================ //

const uploader = new Uploader(Video Uploader, broker);
uploader.subscribe(upload, convert);

const converter = new Converter(Video Converter ${count + 1}, broker);
converter.subscribe(convert, validate);
 
const validator = new Validator(Video Validator ${count + 1}, broker);
validator.subscribe(validate, null); 

// ================ User ================ //

const userA = new Publisher(User A, broker, upload);
const video = new Video(The c programming language, medium);
userA.publish(video);

const userB = new Publisher(User B, broker, upload);
const newVideo = new Video(Me at the zoo, short);
userB.publish(newVideo);

위 구조를 표현하는 클래스를 mermaid 로 만들어줄 수 있나요? 
```

#### 결과

<img width="916" height="884" alt="image" src="https://github.com/user-attachments/assets/addb5cf5-470d-4251-92c8-38212664f170" />
</details>


<details>
<summary>버전 관리 도구</summary>

#### 내용

이번에는 간단하게 참조 관계를 표현하고 이를 바탕으로 다이어그램을 그려 달라고 부탁했다.
이전 대화에서 AI 를 사용하면서 작성한 코드들이 있었기 때문에 이를 기억하여 표현해줄 수 있을 것이라 생각했다.
디테일한 필드와 메서드는 직접 수정했다.

#### 프롬프트

```
Git 이 Repository 를 참조하고,
Repository 가 Index, ObjectDatabase 를 가지고,
GitObject 가 Blob, Tree, Commit 을 상속시키는 구조를 mermaid 로 그려줄 수 있나요?
```

#### 결과

<img width="912" height="880" alt="image" src="https://github.com/user-attachments/assets/b6ea2b69-313e-46e1-96a8-7ec88659cf63" />
</details>

<details>
<summary>느낀점</summary>

다이어그램을 그리니 확실히 구조가 눈에 잘 들어오는 것 같다.

그리는 것이 좋다는 것을 알면서도 시간이 오래 걸릴 것 같아 망설인 적이 많았는데 앞으로는 AI 를 사용해서 빠르게 그려 볼 생각이다.

AI 의 활용성이 참 다양한 것 같다.

</details> 

### J218\_이태호 - 📊 AI 프로젝트 시각화 매니저(개선버전: 예제 프롬프트 추가)

`선택한 이유`
직접 그린 다이어그램보다 시각적으로 보기 좋은 부분도 있을 것이고, 내가 놓친 흐름을 찾아서 연결하고 작성해준다는 점과 마크다운 문서에서 mermaid 엔진을 사용해서 보여주는 부분이 맘에 들어서 선택하게 되었다.

**퀘스트 결과**

<img width="921" height="568" alt="Image" src="https://github.com/user-attachments/assets/101e3422-dee3-468e-a5c2-71555243dc7a" />

**느낀 점**
확실히 손이나 글로 작성하는 방법보다는 보기에도 깔끔하고 피어 피드백, 피어 컴파일링 시 팀원분들도 이해하기 쉽다는 피드백이 있었다. 설계를 애매하게 작성한 경우에는 ai가 의도와 다른 다이어그램을 작성해주기도 해서 설계를 잘 작성하고 ai에게 추가적인 설명을 해서 다이어그램을 작성하게 하는 방식으로 진행했던 것 같다.

### J261\_지현동 - 퀘스트 1: AI 프로젝트 시각화 매니저(개선버전: 예제 프롬프트 추가)
- 피어 피드백 시간에 시각화한 자료의 유무가 토론의 질을 향상시키는 것을 느꼈습니다. 시각화 자동화툴을 사용해본적이 없는데, mermaid엔진을 활용해서 생산성을 챙겨보려고 합니다.

`퀘스트 결과`

<img width="965" height="850" alt="image" src="https://gist.github.com/user-attachments/assets/ea186a58-2b94-4873-8567-3ce4aa64a3bd" />

`느낀점`
AI를 통해 mermaid 엔진으로 해당 코드를 정리해 달라고 했습니다. 제대로 결과물이 안 나와서 여러번 시도해야했고, 프롬프팅을 많이 신경써야함을 알게되었습니다. 앞으로 시각화 자동화툴을 더 적극적으로 사용해보려 합니다.

### K004\_김동경 퀘스트4 AI 모의 면접관
<img width="969" height="500" alt="image" src="https://github.com/user-attachments/assets/1745dde6-5576-4db8-ae65-553299c035a0" />
<img width="627" height="385" alt="image" src="https://github.com/user-attachments/assets/a7e29668-d492-43f4-8612-45d0fd090d29" />
<img width="887" height="319" alt="image" src="https://github.com/user-attachments/assets/26157806-0660-497e-abe5-055951ecc4ce" />
느낀점 <br>
- AI를 통해 나의 학습 내용을 검토할 수 있었고 거의 알고있다고 생각한 내용이였지만 더 보완할 내용과 추가하면 깊이있는 대답이 
될 수 있다는 피드백을 통해 AI를 통해 나의 학습 내용을 검증할 수 있고 내가 어떤 부분을 놓쳤는지 확인할 수 있어 이러한 부분에 있어 학습을 더 깊이 있게 활용할 수 있어
기억에 오래남아 좋았고 앞으로도 학습 정리 후 AI를 통해 검증하는 과정을 거칠려고 합니다.
# 🧰 Node-Red
Flow 기반 프로그래밍으로, 시각적 표현에 매우 적합하고 사용자가 보다 쉽게 접근할 수 있는 모델
노드를 통해 플로우를 이해하고 각 노드 내의 개별 코드 줄을 이해할 필요가 없음

> Flow 기반 프로그래밍?  
> : 응용 프로그램의 동작을 "블랙박스" 프로세스 네트워크로 정의  
> 사전 정의된 연결을 통해 이동하는 정보 패킷을 통해 통신하고, 끝없이 다시 연결되어 내부적으로 변경하지 않고도 다른 애플리케이션 형성 가능

<br>

> Node-Red의 기본 동작
> - 데이터가 주어진다
> - 해당 데이터로 무언가를 수행한다
> - 해당 데이터를 다시 전달한다

<br>

> 다수의 노드를 사용하여 요구사항에 맞는 플로우를 만드는 과정을 시각적으로 표현

<br>

## 브라우저 기반 플로우 편집

- 노드레드의 **팔레트**를 통해 플로우를 쉽게 연결할 수 있는 브라우저 기반 플로우 편집기 제공  
- 제공된 리치 텍스트 편집기를 통해 JavaScript 함수를 작성  
- 내장된 라이브러리를 통해 각종 기능, 템플릿, 플로우를 재사용 가능

<br>

## Node.JS 기반
가벼운 Node.JS 기반으로 이벤트 기반의 모델을 최대한 활용

<br>

## 소셜 개발
노드레드에서 생성된 플로우는 JSON 형식의 데이터를 사용하여 저장되며, 다른 사람과 공유하기 위해 쉽게 import 및 export 가능  
노드레드 홈페이지 - Flows 메뉴에서 공개된 플로우를 공유하여 추가 및 재설계 가능

# 01. 협력하는 객체들의 공동체

### **역할, 책임, 협력**

; 손님, 캐시어, 바리스타의 예시로 설명하고 있음

**요청**과 **응답**으로 구성된 **협력**

협력의 성공은 특정한 역할을 맡은 각 개인이 얼마나 요청을 성실히 이행하는가에 달려 있음

특정한 역할은 특정한 책임을 암시함

동일한 요청(커피 주문)에 대해 서로 다른 방식(커피 아트, 향기 극대화 등)으로 응답할 수 있는 능력을 **다형성**이라고 함

외부의 요청이 무엇인지를 표현하는 **메시지**와 요청을 처리하기 위한 구체적인 방법인 **메서드**를 분리하는 것은 객체의 자율성을 높이는 핵심 메커니즘. 이것은 캡슐화라는 개념과도 깊이 관련돼 있음

클래스는 객체들의 협력 관계를 코드로 옮기는 도구에 불과함

→ 클래스의 구조와 메서드가 아니라 객체의 **역할, 책임, 협력**에 집중하라!

**→ 객체는 클래스가 아니다!!**

# 02. 이상한 나라의 객체

> 객체의 다양한 특성을 효과적으로 설명하기 위해서는 객체를
**상태(state), 행동(behavior), 식별자(identity)**
를 지닌 실체로 보는 것이 가장 효과적이다.
>

토끼, 음료, 케이크, 버섯, 앨리스 등 모두가 뚜렷한 경계를 가지며 **식별** 가능하고 **상태**와 **행동**을 지니고 있음

객체의 프로퍼티는 단순한 값인 속성과 다른 객체를 가리키는 링크의 두 가지 종류의 조합으로 표현할 수 있음

객체지향의 기본 사상은 **상태**와 **상태를 조작하기 위한 행동**을 하나의 단위로 묶는 것이라는 점을 기억하라!

협력에 참여하는 훌륭한 객체 시민을 양성하기 위한 가장 중요한 덕목은 상태가 아니라 행동에 초점을 맞추는 것

⇒ 객체를 설계할 때 상태보다 필요한 행동이 무엇인지 먼저 고려해라!

**“행동이 상태를 결정한다”**

e.g.) **음료를 마시는** 행동 → 앨리스의 **키**가 커짐

행동(음료를 마심)이 상태(키)를 결정함

*객체는 “능동적”, “자율적”*

e.g.) 앨리스가 음료를 마실 때 앨리스가 직접 음료라는 객체의 속성(음료의 양)을 수정할 것이 아니라,

음료를 마시겠다는 **요청**을 보내서 남은 음료의 양을 줄이는 행동을 음료가 **능동적**으로 행하게 함

> 객체지향 설계자로서 우리의 목적은 현실을 모방하는 것이 아니다.
단지 이상한 나라를 창조하기만 하면 된다. 현실을 닮아야 한다는 어떤 제약이나 구속도 없다.
여러분이 창조한 객체의 특성을 상기시킬 수 있다면 현실 속의 객체의 이름을 이용해 객체를 묘사하라.
그렇지 않다면 **깔끔하게 현실을 무시하고** 자유롭게 여러분만의 새로운 세계를 창조하기 바란다.
>
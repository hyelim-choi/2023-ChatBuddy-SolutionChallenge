#  👀 2023 Solution Challenge - CHATBuddy 챗벗

<img width="812" height="375" alt="image" src="https://github.com/user-attachments/assets/5bae9842-6388-4f8c-bedd-636601e8b3ea" /> <br/>
📅 2023.01 ~ 2023.03

# CHATBuddy란?

ChatBuddy는 정신건강 서포터로서 당신의 정신건강을 책임집니다.  
나의 상황, 감정을 누군가에게 부담없이 털어놓고 싶을 때 ChatBuddy를 찾아주세요.  
평범한 일상의 대화를 통해 불안의 원인을 파악하고, 데일리 솔루션을 받을 수 있어요.

더이상 혼자 고민하지 마세요! 😀  

청년들이 자신의 감정을 솔직하게 털어놓고 치유할 수 있는 공간입니다.  
언제 어디서든 무료로 이용할 수 있어요.  
저희 앱의 최종 목적은 청년들의 정신 건강을 지원하고, 감정 조절 능력을 향상시키는 데 도움을 주는 것입니다.

---

## 왜 ChatBuddy인가요?

'Chat'은 대화를 의미하며, Buddy는 친구같은 AI를 의미합니다.  
그리고 'Chat 대화'로 치유의 **Bud 싹🌱**을 틔우겠다는 의미를 담아 팀 이름을 **ChatBud**으로 짓게 되었습니다.

---

## GDSC Solution Challenge란 뭔가요?

> GDSC SWU는 Google Developers가 후원하는 서울여자대학교 학생 개발자들을 위한 대학생 커뮤니티 그룹입니다.  
> 현실에서 마주하는 사회 문제의 해결 방안을 제시함으로써 사회에 긍정적인 영향을 미치는 개발자 커뮤니티가 GDSC SWU의 비전입니다.
>
> 그리고 GDSC 솔루션 챌린지는 UN의 17가지 지속 가능한 개발 목표는 중 하나를 선택하여 해결하는 글로벌 규모의 컨테스트입니다!
> UN의 17가지 지속 가능한 개발 목표 중 <br/>
> **Good Health & Wellbeing** <br/>
> **Peace, Justice & Strong Institutions** <br/>
>
> 을 목표로 한, 팀 `ChatBud`에서 `GDSC Solution Challenge`에 참여해 개발한 마음의 우울감을 없애주기 위한 친구같은 AI 채팅 서비스입니다.


---

## 왜 개발했나요?
1. OECD 자살률 1위 & 코로나19로 인해 높아진 자살률

한국은 OECD 자살률 1위라는 오명을 갖고 있습니다. 그리고 코로나19로 인해 자살률은 더욱더 높아지고 있습니다. 특히, 10대부터 30대 사망 원인 1위는 자살입니다. 10만 명당 자살률 25.7명으로 OECD평균의 2.1배 이상입니다.

2. 부족한 상담 인력

하지만 높아지는 수요에 비해 전문 상담 인력은 매우 부족한 실정입니다. 자살 충동을 느낀 사람들이 상담 전화를 걸어도 통화 연결이 매우 오래 걸리거나 아예 연결이 되지 않는 경우도 있습니다. 수요는 20배 증가했지만, 응대율은 57.9%에 불과합니다. 충동성이 높고 인내심이 부족한 자살 고위험군들에게는 이러한 순간이 견디기 힘듭니다. 또한 자살 충동이 가장 많이 드는 시간대인 새벽에 특히 연결이 쉽지 않습니다.

또한 자살예방상담은 ‘1393’로, 정신건강(자살예방 제외), 아동/노인 학대는 ‘129’로 개편되었는데 개편되지 않은 안내 체계로 인해 상담을 원하는 사람들에게는 혼란이 가중되고 있습니다.

[마지막 생명의 끈인데…상담전화 3분의 1이 '먹통' / SBS](https://www.youtube.com/watch?v=rzwI6BI8td4&feature=youtu.be)

["모든 상담사가 통화중입니다"...연결되지 않는 자살예방상담전화 / YTN](https://www.youtube.com/watch?v=OAEQ4cr1rpw&feature=youtu.be)

[[제보는 MBC] '자살 예방' 핫라인? 전화 안 받고 상담 안 되고‥ (2023.01.12/뉴스데스크/MBC)](https://www.youtube.com/watch?v=FIEZTtT3pLc&feature=youtu.be)

3. 상담사의 고강도 감정노동

저임금과 고강도 감정노동으로 인해 상담사들의 퇴사율은 73%에 달합니다. 이런 실정은 인력 부족을 더욱 심화시키고 있습니다.

["유서에 네 이름 쓰고 죽을거야" 자살 예방 상담을 하며 들은 말들 / 스브스뉴스](https://www.youtube.com/watch?v=Gv8czh-STFQ&feature=youtu.be)

4. 정신 건강 서비스의 낮은 접근성

많은 청년들이 정신 건강 문제를 앓고 있음에도 불구하고 정신질환에 대한 사회적 스티그마에 의해 진단과 치료를 받지 못하고 있습니다. 이는 대한민국의 정신 건강 서비스의 접근성이 낮기 때문이며, 또한 이러한 서비스를 이용하면서 받는 사회적인 편견과 차별들이 두렵기기 때문입니다.

따라서 팀 `ChatBud`는

- 정신 지원 서비스의 인력 부족 문제 <br/>
- 상담사들의 2차 피해 문제 <br/>
- 정신과 방문에 대한 사회적 두려움 문제 <br/><br/>
를 해결하기 위해 이 앱을 기획하게 되었습니다. 저희는 이 앱을 통해 청년들의 정신건강 관리를 강화하고, 국내 정신건강 문제에 대한 사회적 인식을 높이는 데 기여할 수 있기를 기대합니다.

## Architecture
![정보구조도-01](https://user-images.githubusercontent.com/68415422/229152123-844c2c1f-1f41-4fda-856a-26a6716cf587.jpg)

## Features

### Chu-ddy 츄디 <br/>
<img src = "https://user-images.githubusercontent.com/68999618/227910711-3289e617-a6c0-4b87-b770-a48b2e3aaf61.png" width="10%" height="10%">

안녕하세요! 츄디예요 :)  <br/>
츄디는 여러분들을 위한 `걱정인형`이에요. 불안함과 걱정 때문에 밤새 뒤척인 적이 있으신가요? 걱정인형은 잠들기 전 걱정을 들려주고 베개 밑에 두면 이 인형이 걱정을 가져가 밤새 뒤척이지 않고 잘 수 있다는 과테말라의 전설에서 유래했습니다. 츄디가 여러분의 `걱정인형`이 되어 모든 불안과 우울을 가져가 줄게요! 여러분의 생각과 고민들을 들려주세요. <br/> <br/>

### 상세페이지
**회원가입/로그인**  <br/>

<img src="https://github.com/user-attachments/assets/86d0292f-4233-4f75-a09a-c2fd1fd3b728" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/79e81125-e39c-4c77-a1d3-92327fcb1324" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/58a1b362-87fb-4c0c-a63e-6fbdf65b0358" width="25%" height="25%"/>
<br/><br/>

**채팅**  <br/>

<img src="https://github.com/user-attachments/assets/2a7a90bb-4945-4309-99c8-8b9c4aa0dd16" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/510ef963-60bb-4c63-aabc-28488afab937" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/ac528122-a53d-4387-b36a-135e0fab7af0" width="25%" height="25%"/>
<br/><br/>

**솔루션**  <br/>
<img src="https://github.com/user-attachments/assets/9f5072e9-b1f3-4dda-8009-09ce149cb8f9" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/f03e1b98-37fc-40c7-9f63-fb56ffa5896e" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/fd832b53-1352-47f1-af53-07d3a5b76ed7" width="25%" height="25%"/>

<img src="https://github.com/user-attachments/assets/45e07721-893b-4d1b-ae7d-2d72bb3916f5" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/a65d9453-60d2-42f6-998b-82fb9c897a6e" width="25%" height="25%">
<img src="https://github.com/user-attachments/assets/8be91af5-b9d5-4382-9d37-70fdd89773c1" width="25%" height="25%">


## Demo
[![thumbnail](https://user-images.githubusercontent.com/68415422/229873666-0d2a5e4a-936d-493d-a1be-5e50cf1ce293.JPG)](https://www.youtube.com/watch?v=Clnm2T3QIpY)

## Team members
👩🏻‍💻 김정현(Jeong-Hyeon Kim) <br/> 
👩🏻‍💻 이정인(Jeong-In Lee) <br/>
👩🏻‍💻 조예원(Ye-won Jo) <br/>
👩🏻‍💻 최혜림(Hye-lim Choi) <br/>

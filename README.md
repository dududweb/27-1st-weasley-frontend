
## 프로젝트 개요
2주간의 짧은 개발기간으로 인해 디자인,기획만 클론하였으며 데이터, 기능구현은 자체적으로 만들었습니다.


## 프로젝트 기간

- 2021.11.29. ~ 2021.12.10.

# Members

[프론트엔드]  
[김유량 Github](http:s//github.com/YuryangKim)  
[황성재 Github](https://github.com/seongjae0325)  
[황주영 Github](https://github.com/dududweb)

<br/>

[백엔드]  
[강태준 Github](https://github.com/eslerkang)  
[길동화 Github](https://github.com/dk-sync)  
[염기욱 Github](https://github.com/bakha1002)

## <b>목표</b>

- 그동안 학습했던 지식들을 2주 간의 팀 프로젝트에 활용
- 초기 세팅부터 전부 실제 사용할 수 있는 서비스 수준으로 기획 및 배포까지 구현

---

# 구현 영상

사이트링크: http://18.216.61.230:8000/

---


# 프로젝트 담당업무
- 상세페이지: 서버와의 통신으로 UI를 렌더링 하였으며 구매하기 버튼 클릭시 서버에게 post 요청을 보내 장바구니로 전달되게 했습니다. 
- 구매버튼 클릭 시 post 요청을 중첩 사용하여 서버에 요청을 했습니다.
- 구독버튼 클릭 시 분기처리하여 조건부렌더링하였고, get, post 요청을 중첩 사용하여 렌더링했습니다. 회원의 주소가 존재할 시에는 주소입력창 대신 구독완료 알럿이 노출됩니다.
- 오더페이지: 조건부 렌더링으로 화면 ui를 렌더링하며 초기 주소가 없다면 post요청으로 등록하고 get으로 렌더링해줍니다. 포인트 결제 후 포인트 차감기능까지 구현하였습니다.
- 푸터: 반복적인 UI를 상수데이터화하여 map 매서드를 이용하여 렌더링했습니다. 
- 메인페이지: 유지보수와 빠른 작업을 위해 flex레이아웃으로 작업했습니다.
![상세페이지뷰](https://user-images.githubusercontent.com/91524565/145734795-1f61a2e0-ef43-43a6-b13e-3329673d953c.gif)
![구독주소알럿](https://user-images.githubusercontent.com/91524565/145735215-6e5e195d-a41f-46b2-afee-c780922a94f1.gif)
![오더부분](https://user-images.githubusercontent.com/91524565/145735371-b75e3fef-6a15-4e4d-b1bf-df240167fbc7.gif)


# 프로젝트 회고

## 배운 점

1. fetch를 통한 서버와의 통신 방법을 알게 되었습니다.
2. state 관리와 불변성에 대해 이해하게 되었습니다.
3. scss 활용
4. 팀단위에 트렐로 관리와 협업의 중요성에 대하여 알게되었습니다.

<br/>

## 느낀 점

1. 팀 단위의 프로젝트를 통해 의사소통 능력 향상 및 협업의 중요성과 이해도를 향상 시키는 계기가 되었습니다.

2. 공통적인 목적성을 가지고 프로젝트를 진행해볼 수 있는 기회가 있어서 좋았고, 백엔드와 실질 적인 통신을 해봄으로써, API에 대한 전반적인 이해도가 향상 되었습니다.

3. 리액트적 사고와 문법에 대해 기본적인 이해와 리액트에 대한 지적호기심이 더욱 생겼습니다.

<br/>

## 아쉬운 점

1. 기능 구현에 초점을 맞춰서 사용자 중심의 UI를 고려하지 못했다. 그에 따라 CSS의 완성도가 부족했던 것 같습니다.

2. 첫 주의 협업 툴의 사용시에 있어서 업무 세분화가 체계적으로 안되어 아쉬웠지만, 2주차 때 checklist 활용을 통해서 업무를 분배하고 진행습니다.

---

# SKillS

- HTML
- CSS
- Sass
- JavaScript(ES6)
- React.js
- Git

# Reference

- [API Document](https://docs.google.com/spreadsheets/d/1VEnmoeMfSquz6PnfTI9717p0FvRqJzT_ZRAklIup-lY/edit?usp=sharing)
- 이 프로젝트는 [와이즐리 오픈워크](https://openwork.wiselycompany.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.

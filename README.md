**멋쟁이사자처럼 11기 운영진 1주차 사전과제**

## Tech Stack

- html
- css
- javascript

## Folder structure

```
├── js
│   ├── Todo  
│   │   ├── addTodo.js
│   │   │
│   │   ├── displayTodo.js
│   │   │
│   │   └── deleteTodo.js 
│   │   
│   ├── data.js
│   │   
│   └── main.js
│  
├── index.css
│   
├── index.html
│   
└── README.md
```

## 중요하게 생각한 요소

'다른 사람이 알아보기 쉬운 코드' 라는 것에 목표를 맞추고 시작하였는데, 막상 코드를 작성하니까 이 기능 구현, 저 기능 구현 이렇게 짜다보니 알아보기 어려운 코드가 되어 버리더라구요.
역시 코드를 짜기 전에 먼저 어떤식으로 시작 할지에 대한 그림이나 구성을 생각하는게 중요하다 라는걸 다시금 느꼈습니다.
어느정도 기능이 완료되고 난 뒤에 함수 분리를 하려다 보니 오류가 발생할때 어디서 발생한지 찾기가 참 어려웠습니다.
그래도 기능별로 함수를 나누고 알아보기 쉽도록 정리해 보려고 노력하였습니다!


#### 커밋 컨벤션

| 머릿말   | 설명                               |
| -------- | ---------------------------------- |
| feat     | 기능 구현                          |
| setting  | 패키지 설치, 개발 설정             |
| refactor | 기능변화 없이 최적화, 코드 개선 등 |
| fix      | 버그 수정                          |
| style    | 스타일링, 변수명 수정              |
| docs     | README.md 작성,주석 추가           |

#### 브랜치 네이밍 컨벤션

모든 feature는 dev에서 분기

| 머릿말  | 설명                        |
| ------- | --------------------------- |
| master  | 최종 결과                   |
| dev     | 기능 구현                   |
| feature | 기능 단위 구현              |
| fix     | master에서 발견된 버그 수정 |

# kakao_clone

## 목차
  - [개요](#개요)
  - [기획](#기획)
  - [실행환경](#실행환경)
  - [구현기능](#구현기능)
  - [참조](#reference)

## 개요
- 프로젝트 이름 : kakao_clone 코딩
- 프로젝트 기간 : 2022.04.10 ~ 2022.05.09
- 개발 언어    : html, css
- 사용 tool   : vscode

## 기획
- 기획의도 : html5 css3 학습 목적 클론 코딩

## 실행환경
- Tool : vscode
- Language : html5, css3

## 구현기능
- github pages :  https://taewan625.github.io/kakao_clone/
- 학습 기능
  - a tag, img 상대경로, 절대경로
  - external css, inline css
  - block, inline
  - margin, padding, border
  - collapsing margin : block들의 상하가 같은 line에 존재시 같이 움직이는 현상
  - inline 요소 : padding 상하좌우 적용, margin 좌우 적용
  - id: unique, 1개
  - class: 중복 가능, 여러이름 가능
  - pseudo selectors
  - state
    - active: click 시 변화
    - hoverover: mouse가 대상 위에만 있어도 변화
    - focus: keyboard로 tap 할 때 변화
    - visted: link에서만 작동을 하고 방문한 site가 원하는 color로 적용
    - focus-within: focused된 자식을 가진 부모 엘리먼트에 적용
    - form:hover input: 이 조건은 form이 hover 되어있고 그 안에 input이라는 것이 존재할 때 적용
     
  - 위치 이동
    - display: flex(부모에게 명시), justify-content, flex-direction, aligin-items
    - text-alignment
  - flex-wrap
    - wrap: 화면창을 줄일때 box 가 크기를 바꾸지 않고 위치가 변하고
    - nowarp: 화면을 바꿀때 box 크기도 줄어들면서 공간을 일정하게 유지
  - position
    - fixed: web page 스크롤을 내려도 계속 유지
    - static: 원래 있는 위치에 놓아두는 것
    - relative: 약간씩 옮겨주는 현상 만든 요소를 기점(=처음 만들어진 기준)으로 시작하여서 조금씩 이동
    - absolute : div가 body의 맨 오른쪽,아래, 왼쪽, 위로 간다는 것 부모 박스를 기준으로 움직이지 않음. 이것은 가장 가까운 relative 부모를 기준으로 이동

  - transition: 변화를 나타내는 동작을 하는 것
  - transform
  - @keyframes



## reference
- nomadCoders.co
- MDN Web docs
- https://flexboxfroggy.com/#ko

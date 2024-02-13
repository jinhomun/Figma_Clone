# FIGMA_CLONE

## 소개

fabric.js를 사용하여 캔버스에 커서 채팅, 댓글, 반응 및 드로잉 디자인(모양, 이미지 업로드)을 통한 실시간 공동 작업과 같은 실제 기능을 추가하는 방법을 보여주는 최소한의 Figma 복제본입니다.

## 설치

```js
npx create-next-app@latest

npm i fabric uuid @liveblocks/client @liveblocks/react
npx create-liveblocks-app@latest --init --framework react

npx shadcn-ui@latest init
Need to install the following packages:
shadcn-ui@0.8.0
Ok to proceed? (y) y
√ Which style would you like to use? » Default
√ Which color would you like to use as base color? »
Slate
√ Would you like to use CSS variables for colors? ... no / yes

npm i @liveblocks/react-comments

```

## 특징

👉 멀티 커서, 커서 채팅 및 반응 : 개별 커서 표시, 실시간 채팅 및 대화형 커뮤니케이션을 위한 반응을 활성화하여 여러 사용자가 동시에 협업할 수 있습니다.

👉 활성 사용자 : 협업 환경에서 현재 활성 사용자 목록을 표시하여 현재 참여 중인 사용자에 대한 가시성을 제공합니다.

👉 댓글 풍선 : 사용자가 캔버스의 특정 요소에 댓글을 첨부하여 디자인 구성 요소에 대한 커뮤니케이션과 피드백을 촉진할 수 있습니다.

👉 다양한 모양 만들기 : 사용자가 캔버스에 다양한 모양을 생성할 수 있는 도구를 제공하여 다양한 디자인 요소를 허용합니다.

👉 이미지 업로드 : 이미지를 캔버스로 가져와 디자인의 시각적 콘텐츠 범위를 확장합니다.

👉 사용자 정의 : 사용자가 디자인 요소의 속성을 조정할 수 있도록 하여 시각적 구성 요소를 사용자 정의하고 미세 조정할 수 있는 유연성을 제공합니다.

👉 Freeform Drawing : 사용자가 캔버스에 자유롭게 그림을 그릴 수 있어 예술적 표현과 창의적인 디자인을 촉진합니다.

👉 실행 취소/다시 실행 : 이전 작업을 취소(실행 취소) 또는 복원(다시 실행)하는 기능을 제공하여 디자인 의사 결정에 유연성을 제공합니다.

👉 키보드 작업 : 사용자가 복사, 붙여넣기, 삭제, 커서 채팅 열기, 반응 등과 같은 기능에 대한 단축키 실행을 포함한 다양한 작업에 키보드 단축키를 활용할 수 있도록 하여 효율성과 접근성을 향상시킵니다.

👉 내역 : 캔버스에서 수행된 작업 및 변경 내역을 시간순으로 검토하여 프로젝트 관리 및 버전 관리에 도움을 줍니다.

👉 캔버스 삭제, 크기 조절, 이동, 지우기, 내보내기 : 삭제, 크기 조절, 이동, 캔버스 지우기, 최종 디자인을 외부로 내보내기 등 디자인 요소를 관리하기 위한 다양한 기능을 제공합니다.

코드 아키텍처, 고급 반응 후크 및 재사용성을 포함한 더 많은 것

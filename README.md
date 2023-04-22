# JS\_*Game*만들기

JavaScript를 이용해서 게임 만들기 모음 // css 보충하기

- 처음 구현시 정답 칸마다 각각 한번씩 마우스로 직접 클릭을하고 키보드로 타이핑을 해야하는 불편한점을 발견
  (인풋 리스트별 해당 칸에 정답 일력시 자동으로 다음칸으로 포커스를 통해 커서 깜빡임 이동.)

- 이후 5개의 정답 칸을 입력할시에 칸에서 칸으로 넘어가는 부분에서 다시 한번 마우스를 통해 이동하거나
  탭키를 이용하여 넘어가서 정답을 입력해야하는 불편함이 존재
  (개선 - 자동으로 칸을 넘어가도록 구현)

- 제출 버튼을 클릭을 통해 정답을 제출해야 하는 불편함이 존재
  (제출 버튼을 클릭으로 정답을 제출이 아닌 엔터키를 통해 사용자가 자연스럽게 정답을 제출하도록 개선)

- 게임 결과 승리, 실패를 사용자 혼자만 알 수 있었던 부분과 결과를 알려주는 부분이 없어 불편함이 존재
  (알람을 띄어주는 기능을 연결해 승,패 결과와 정답시 한번에 알 수 있도록 구현)

# 앞으로의 구현 방향

- 정답란에 잘못 입력시 마우스 커서로만 각각의 칸을 눌러 다시 수정해야 하던 부분을 키보드 방향키를 통해
  쉽게 수정할 수 있도록 개선할 예정.

- 영단어 버전, 한글 버전등 언어별 와들을 구별지어 다른 언어 입력시 알림이 안뜨고 그냥 진행되던 오류부분을
  개선할 예정.

# 최종목표

- ** 와들게임을 단지 정답만 맞추는게아닌 사용자들의 흥미와 경쟁심 유발을 위해
  정답 시간 체크 기능을 통해 랭킹 시스템을 도입하여 사용자간 순위를 닉네임 입력을 통해 확인할 예정. **

- 엔터 수정
- **단어별 난이도**
- 국가별 언어 설정 sns 본인 레코드 기록 공유 기능 구현
- 본인 캐릭터 및 닉네임

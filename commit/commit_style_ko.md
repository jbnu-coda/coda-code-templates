# 시맨틱 커밋 메세지 - 확장판

커밋 메시지 스타일을 조금만 변경해도 어떻게 더 나은 프로그래머가 될 수 있는지 알아보세요.

명확한 범위 표시를 중간에 추가함으로서 더욱 쉽게 알 수 있습니다.

Format: `<유형>: (<범위>): <제목>`

`<범위>` 는 선택사항힙니다.

## 예시

```
feat: Main.java: add hat wobble
^--^  ^-------^  ^------------^
|     |          | 
|     |          +-> 현재 시제로 요약합니다.
|     |
|     +------> 명확한 범위로 표기합니다.
|
+-------> 종류: chore, docs, feat, fix, refactor, style, 혹은 test.
```

더 많은 예:

- `feat`: (빌드 스크립트를 위한 새로운 기능이 아닌 사용자를 위한 새로운 기능)
- `fix`: (빌드 스크립트에 대한 수정이 아니라 사용자를 위한 버그 수정)
- `docs`: (문서 변경 사항)
- `style`: (포맷팅, 세미콜론 누락 등; 생산 코드 변경 없음)
- `refactor`: (프로덕션 코드 리팩터링, 예: 변수 이름 바꾸기)
- `test`: (누락된 테스트 추가, 테스트 리팩토링; 프로덕션 코드 변경 없음)
- `chore`: (귀찮고 하기싫은 작업 혹은 업데이트 등; 프로덕션 코드 변경 없음)

참조:

- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
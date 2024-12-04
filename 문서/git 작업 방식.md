# git 작업 방식

## 커밋 메세지 작성 예시

```scss
feat: add EDA_Sleep_BMI
```

```scss
docs: add 12월 1일 회의록
```

```scss
fix: 하루수면량 결측치 처리 오류 수정
```

```scss
refactor: remove scatter plot, add lmplot
혹은,
refactor: scatter plot 제거 후 lmplot으로 교체
등등 ..
```

→ 요건 vscode에서 커밋 메시지 작성할 때 쓰시는 방식입니다

## Github Pull request 작성 방법

- `제목`  : [커밋 컨벤션] 커밋 메시지
- `내용`  : `-` 와 함께 커밋 내용 간략히 설명.

### 예시

```markdown
[FEAT] EDA_Sleep_BMI 추가

- 수면 시간과 BMI에 대한 EDA 작업 진행한 코드 추가했습니다.
```
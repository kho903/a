# Review
## Review 받는 법
1. 먼저 새로운 branch 내에 리뷰하고 싶은 코드를 올린다.
	1. 새로운 브랜치 만드는 법
	- `git branch 브랜치이름`
	2. 새로운 브랜치로 이동
	- `git checkout 브랜치이름` 또는
	- `git switch 브랜치이름`
	3. 새로운 브랜치에 리뷰받고 싶은 코드를 만들어 푸시한다.
2. 푸시한 코드를 main 브랜치에 pull requests를 날린다.
	- 이 때, 리뷰어를 reviewer에 등록한다.
3 - 1. 리뷰어가 Approve를 하게 되면 main에 merge할 수 있는 상태가 된다.
3 - 2. 상대방이 comment를 보고 코드를 고친 뒤, 다시 2번을 반복 할 수 있다.

## Review 하는 법
1. 리뷰어는 Pull requests에서 Add your review클릭한다.
2. 소스코드에 Comment를 남기고 싶다면, 코드 내에 + 버튼을 눌러 Comment를 남긴다.
3. 3가지 방식으로 완료 할 수 있다.
- Approve : 승인
- Comment : Comment 작성
- Request changes : 코드 수정 요구

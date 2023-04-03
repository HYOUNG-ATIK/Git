## Git Commit Message Convention

기업마다 rule이 다르겠지만 대표적인 예시로 가져옴

### 커밋 메시지 형식
```
[type] Subject
[body]
[footer]
```
- **[type] 예시**
    - ***feat*** : 새로운 기능 추가
    - ***fix*** : 버그 수정
    - ***docs*** : 문서 내용 변경
    - ***style*** : 포맷팅, 세미콜론 누락, 코드수정x 등
    - ***refactor*** : 코드 리팩토링
    - ***test*** : 테스트 코드 작성
    - ***chore*** : 빌드 수정
    
- **Footer**
    - 이슈 트래커의 ID
    - 어떤 Issue와 관련된 ***commit***인지
    - ***See also***(그 외 참고사항)

<br>

### 커밋 메시지 예시
```
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```
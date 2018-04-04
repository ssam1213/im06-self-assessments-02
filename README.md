# Week 02 Self-Assessment

## Guidelines

- Self-assessments 를 하면서 최근에 학습한 부분들을 얼마나 잘 이해했는지 판단할 수 있습니다.
- 모든 self-assessments 는 완료후 반드시 pull request 를 해야 합니다(아래 가이드라인 참고). 배정된 시간에서 pull request 를 할 시간을 꼭 가지길 바랍니다.
- 모든 문제를 조금이라도 해결하려고 시도하기 바랍니다. 아무 시도도 안하고 그대로 두는것보다 pseudo-code 를 작성하거나 본인의 접근방법을 코멘트로 적는게 더 좋은 평가를 받을 것입니다.
- TIP: Chrome Console, [JSFiddle](https://jsfiddle.net/) 을 활용해서 작성한 코드가 제대로 작동하는지 빠르고 쉽게 테스트할 수 있습니다.

## Grading Outline

- [ ] algo-time-complexity
- [ ] js-inheritance-pseudo-classical-alt
- [ ] chat-client-fixme

## Using and Referencing Outside resources

각 문제들에는 참고 가능한 외부자료들의 목록이 포함되어 있습니다. 테스트중에 이전에 본인이 풀었던 코드, 다른 사람이 올린 코드등을 보는건 금지되어 있습니다. 참고 가능한 외부자료들의 목록 이외에 본인이 문제를 풀때 참고했던 자료들이 있다면 그 자료들의 목록을 각 문제에 코멘트로 적어주시기 바랍니다.

## Self-Grading Process

각 문제들을 푼 후, `README.md` 파일을 수정해서 grade 를 작성하시면 됩니다. 위의 Grading Outline 섹션의 [ ] 에 grade 를 스스로 매기시길 바랍니다. ([Grading Scale](/grading-outline.md) 를 참고)

## Submitting Solutions

Solutions 은 [Pull Request](https://help.github.com/articles/using-pull-requests) 를 통해 제출합니다. 아래 순서대로 제출해주세요:

1. **여러분의 fork** 에서 `Pull Requests` 를 선택하고, `New pull request` 를 생성합니다.
2. Pull Request 의 comment block 에 Grading Outline 을 채워넣고 복사해 붙입니다. [grading-outline](/grading-outline.md) 참고
3. `Send pull request` 를 클릭합니다.

---

## Algo Time Complexity

Inside of `algo-time-complexity.js`, identify the time complexity of the following functions:
- [ ] `sortedIndexOf`
- [ ] `findDuplicates`
- [ ] `bruteForcePassword`
- [ ] `hasDuplicates`
- [ ] `removeLastThreeElements`
- [ ] `increasingStep`
- [ ] `makeRange`

### Available Resources for this Prompt
  * MDN

## Pseudo-classical inheritance
* [ ] Rewrite `makeHorse` and `makeFlyingHorse` to use pseudo-classical inheritance
  * They must have all of the same methods as objects returned from the maker functions
  * _Do not modify the factory functions - instead, use the constructor functions at the end of the file_

## Chat Client
This repository is a chat-client like the one you built for Chatterbox Client. It has a (mostly) completed HTML/CSS user interface, but is missing a critical feature:

* [ ] Inside `js/setup.js`, locate the function responsible for sending messages to the server and write a comment to indicate your claim
* [ ] In the method that you identified, make it so that any message sent to the server appears in the chat log as soon as the client knows that the server successfully received them, rather than waiting for a refresh or the timed update

Note that this is an exercise in reading code and code reuse, so expect to spend most of your time figuring out where to make changes and try to write as little code as possible

### Available Resources for this Prompt
* jQuery docs
* MDN

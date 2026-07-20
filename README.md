## 作業はAIに任せても、判断は手放さない。

建築現場で働く非エンジニアです。コードは書けないので、すべてAIに書かせて、
判断だけを自分でやっています。「動く」と「任せられる」のあいだを埋める仕組みを、
作って、自分で使って、試しています。

### 作っているもの

- **[github-task-protocol](https://github.com/shinya0x00/github-task-protocol)** —
  AI coding agentと安全にタスクを進めるためのGitHubネイティブなプロトコル。
  目的・範囲・完了条件を人間が決め、判断の痕跡がGitHubに残る。導入はGTP.md 1ファイル。
- **[agent-operated](https://github.com/shinya0x00/agent-operated)** —
  AIエージェントのGitHub操作を専用のMachine Accountへ分離し、「誰の操作か」を
  常に判別できるようにするOperation Hub（pre-alpha）。

### このアカウント自体が実験です

現在の開発はGTPの進め方で進めており、エージェントによる操作は
machine account（agent-operated-bot）に分離しています。
非エンジニアがAIとの協働でどこまで作れるか、その記録そのものです。

---

X: [@shinya0x00](https://x.com/shinya0x00)

*A non-engineer building software entirely through AI collaboration —
with a protocol that keeps human judgment in the loop.*

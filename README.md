# gigflow-demo-workspace

Demo workspace where a freelance Worker submits PRs reviewed by Agentic Gig-Flow.

## About
  
  Agentic Gig-Flow は、業務委託の発注から検収・JPYC 報酬支払までを AI エージェントが自律完結させるデモワークスペースです。
  3. Commit changes → Create a new branch（名前は add-about など）→ Propose changes
  4. PR 作成画面で、本文に必ず Closes #1 を入れる（← これが無いと Webhook が orderId を解決できません）→ Create pull request
  5. PR ができたら Checks タブで CI（CI / test）が緑✅になるまで待つ
    - ⚠️  CI が緑になる前に私が確認すると、Review Agent が pending 扱いで reject してしまいます

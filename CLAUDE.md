# tech-writing

個人對外技術 / 分享文章集。

## 寫作與協作慣例

- **語言**：正體中文。
- **術語**：能自然中文化的就中文化，但保留業界慣用、硬翻會卡的英文名詞（如 spec、prompt、cache、CI、review、merge、commit、agent）。
- **去業務化（重要）**：這些是對外公開文章，**不得洩漏作者其他私有專案的業務內容**——不出現具體使用者、產品功能、領域術語、私有 spec 的欄位 / feature 名。只談通用的技術 stack 與工程實踐。發布前做敏感詞掃描，確認零洩漏。
- **不走 Spectra**：此 repo 與業務專案刻意隔離，不使用 openspec / Spectra 流程。

## Git

- Conventional Commits（文章多用 `docs:`）。
- 具名 staging，**不用** `git add -A`（避免誤入暫存 / 隱私檔）。
- 每個 Claude 產生的 commit 加 trailer：`Co-Authored-By: Claude Opus 4.7 (1M context) <noreply@anthropic.com>`。
- GitHub：已公開推送；remote `origin` = https://github.com/chingho-chang/tech-writing，`main` 追蹤 `origin/main`。

## 文章

- `sdd-retro-article.md` — spec-driven agentic coding 一週心得：AI 協作如何把寫文件 / 測試從「美德稅」變成副產品。
- `frictionless-collaboration.md` — 〈終於只剩事情本身〉：AI 協作免去面對協作情緒的解脫感，及這份解脫轉移到別處的代價（抒發短文）。

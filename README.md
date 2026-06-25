# Git 協作練習

這個 repo 用來練習 Git / GitHub 的多人協作流程，包含 branch、commit、Pull Request、code review 以及 conflict 解決。歡迎大家在 `members.md` 填入自己的資料，實際走一遍協作流程。

## 練習步驟

1. **clone repo**
   ```bash
   git clone <repo-url>
   cd git-practice
   ```

2. **建立自己的 branch**（命名規則：`feature/你的名字`）
   ```bash
   git checkout -b feature/你的名字
   ```

3. **編輯 `members.md`**，在自己的區塊填入資料

4. **commit**（格式：`feat: add 你的名字`）
   ```bash
   git add members.md
   git commit -m "feat: add 你的名字"
   ```

5. **push 並開 Pull Request**
   ```bash
   git push -u origin feature/你的名字
   ```
   接著到 GitHub 上開一個 Pull Request，target 設為 `main`。

6. **等待其他人 review**，若有 conflict 請先解決，通過 review 後即可 merge。

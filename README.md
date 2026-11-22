# Hi, I'm Nelson (@taipei49314) 👋

在台北的獨立開發者，喜歡持續做兩類東西：
- **日常用得上的開發小工具** — 輕量、本機跑、不追蹤，幫大家省下踩雷的時間。
- **打開就能玩或看的互動作品** — 3D 視覺、短篇互動敘事、數位造型體驗。

Indie developer in Taipei building lightweight, trustworthy everyday dev tools and interactive visual works. Feel free to explore, try them out, or open an issue to say hi!

🌐 **Portfolio / 個人作品頁:** [taipei49314.github.io](https://taipei49314.github.io/)

---

## 🛠️ Developer Tools · 開發工具

- **[checkwash](https://github.com/taipei49314/checkwash)** *(Python · [PyPI](https://pypi.org/project/checkwash/))*  
  送 commit 或開 PR 前快速掃一下 Git diff，幫你抓出測試被不小心刪掉、跳過或寫鬆的地方（特別適合搭配 AI 寫程式時用）。  
  Scans your Git diff locally to catch accidentally dropped, skipped, or weakened tests before you commit or merge.
  - **[checkwash-prove](https://github.com/taipei49314/checkwash-prove)** *([PyPI](https://pypi.org/project/checkwash-prove/))* — 用實際故障測試你的改動是不是讓原本抓得到的 bug 漏掉了 / Runs concrete fault checks to see if a test edit dropped real protection.
  - **[checkwash-lens](https://github.com/taipei49314/checkwash-lens)** *(VS Code · [Releases](https://github.com/taipei49314/checkwash-lens/releases))* — 直接放進 VS Code 側邊欄的即時檢查工具（Win/Linux/WSL2/Dev Containers）/ VS Code sidebar extension for one-click diff & pre-commit checks.

- **[boundary-unpack](https://github.com/taipei49314/boundary-unpack)** *(Linux · Rust + Python · [Releases](https://github.com/taipei49314/boundary-unpack/releases))*  
  在 Linux 上用 `seccomp`、`cgroup v2`、Rust broker 與原子發布安全解壓不可信的 `.zip` / `.tar.gz`，防路徑穿越、炸彈與殘留髒檔。  
  Safely extract untrusted `.zip` and `.tar.gz` archives on Linux inside a `seccomp` + `cgroup v2` sandbox with a Rust `openat2` broker and atomic `renameat2` publication.

- **dllwhy** *(coming soon)*  
  Windows 上 Python 跳 `DLL load failed` 時，一條指令告訴你到底缺了哪個 DLL。  
  One-command, no-admin diagnostic tool that tells you which DLL is missing when a Python import fails on Windows.

---

## ✨ Interactive & Visual Works · 互動與視覺作品

- **[starry-night-3d](https://github.com/taipei49314/starry-night-3d)** · **[Live Demo](https://taipei49314.github.io/starry-night-3d/)**  
  把梵谷《星夜》拆成約 18 萬筆 3D 筆觸撒在 250 公里深的空間裡——從旁邊看是一片星塵，只有回到畫家的視點 *E* 才會拼回整幅畫。  
  Van Gogh's *The Starry Night* scattered as ~181k 3D brushstrokes across 250 km of depth—lining up into the painting from one single viewpoint *E*.

- **沙下迴廊 · The Returning Passage** *(coming soon)*  
  一部 3 分鐘、戴上耳機靜靜看的雙語第一人稱互動短篇與 3D 光影空間展示。  
  A 3-minute bilingual interactive short and 3D light-and-space showcase—best experienced with headphones.

- **Editorial Doll** *(coming soon)*  
  免登入、打開瀏覽器就能自由搭配服飾並匯出高解析海報的數位造型室。  
  A browser-based digital styling studio for composing editorial looks and exporting high-resolution posters—no account required.

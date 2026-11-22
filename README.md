# Nelson · @taipei49314

**本機優先、證據優先 — models propose, verifiers decide.**  
Independent developer in Taipei. Building local-first, deterministic verification tools for software changes and interactive visual works built around one idea: **對得上** (*every stroke has to line up*).

🌐 **Site & Works:** [taipei49314.github.io](https://taipei49314.github.io/)

---

## Verification & Evidence · 驗證與防弱化工具

Tools that check whether tests, diffs, and environments still prove what they claim—locally, deterministically, and with replayable evidence.

- **[checkwash](https://github.com/taipei49314/checkwash)** *(Python · pre-1.0 · [PyPI](https://pypi.org/project/checkwash/))*  
  靜態讀取 Git diff，標出刪除斷言、放寬條件、略過測試與弱化 CI 等已知模式（本地執行、無 LLM、不執行待測程式碼）。  
  Flags known patterns of weakened tests and CI checks in a Git diff—locally, with no LLM and without executing your code.
  - **[checkwash-prove](https://github.com/taipei49314/checkwash-prove)** *(experimental · [PyPI](https://pypi.org/project/checkwash-prove/))* — 反向以具體故障實際執行測試，驗證測試變更是否丟失保護力 / Runs tests against concrete faults to show what protection a test change dropped.
  - **[checkwash-corpus](https://github.com/taipei49314/checkwash-corpus)** — 用於量測 `checkwash` 的真實 Git 歷史語料 / Real Git history corpus used to measure `checkwash`.

---

## Visual & Interactive Works · 視覺與互動作品

- **[starry-night-3d](https://github.com/taipei49314/starry-night-3d)** · **[Live Demo](https://taipei49314.github.io/starry-night-3d/)** *(TypeScript · Three.js)*  
  《星夜，只在一個點成立》— 約 18.1 萬筆程序化筆觸散布在最深 250 公里的 3D 空間，唯有站在畫家視點 *E* 才拼回梵谷《星夜》。  
  *The Starry Night, from One Viewpoint* — ~181k procedural brushstrokes across a 250 km deep anamorphic 3D space that align into Van Gogh's painting from a single viewpoint *E*.

- **[taipei49314.github.io](https://github.com/taipei49314/taipei49314.github.io)** · **[Visit Site](https://taipei49314.github.io/)** *(Plain HTML / CSS / JS)*  
  雙語個人作品頁（零框架、零第三方請求），一併收錄 `checkwash`、《星夜》、*Editorial Doll*（未公開散發）與《沙下迴廊》*The Returning Passage*（製作中）的互動展示與說明。  
  Bilingual personal showcase built with zero frameworks or third-party requests.

# taiwan-status-ihl

An agent skill (Claude Code / Codex / any agent that reads `SKILL.md`) for analysing the legal status of **Formosa (Taiwan) and the Pescadores (Penghu)** and the **human-rights position of their inhabitants** under international law, the law of occupation and international human-rights law — with the primary sources.

## What it gives an agent
- Five source-backed conclusions: (1) the Empire of Japan and the State of Japan are one continuing State; (2) Japan renounced Formosa and the Pescadores in 1952 without naming a recipient, and no later instrument transferred title; (3) the ROC entered as an occupant acting for the Allies; (4) under the San Francisco Peace Treaty neither China (ROC or PRC) nor Korea acquired any title; (5) sovereignty was disposed of, but the inhabitants' rights remain — through occupation law, nationality and human-rights law, self-determination and (for Austronesian peoples) indigenous rights.
- The strongest counter-arguments with replies, UN channels, the difference between "people of the territory" and "indigenous peoples", a list of dead ends, and open verification items.
- `sources/`: 77 folders of treaty, judgment, parliamentary and UN texts with URLs and sha256 of the originals.

## Install
```bash
git clone <this repo> ~/.claude/skills/taiwan-status-ihl     # Claude Code
# or symlink the folder into your agent's skills directory
```

## Method
Every claim is quoted from a text in `sources/`; secondary or unchecked items are marked **[verify]**. Adverse evidence is recorded, not omitted.

## Licence
Analysis text (`SKILL.md`, `references/`, README): CC BY 4.0. Source texts in `sources/` keep their own status (treaties, official records, court decisions and UN documents; see `NOTICE.md`).

---

# taiwan-status-ihl（中文說明）

給 AI agent 使用的 skill：依國際法、占領法（國際人道法）與國際人權法，分析**台灣、澎湖的法律地位**與**當地人民的人權**，並附原始法源。

- 五個結論：日本帝國與日本國是同一國家；日本 1952 年放棄台澎、沒有指定接收者，之後也沒有任何文件移轉主權；中華民國依盟軍命令受降占領；依舊金山和約，中國（兩岸）與韓國都沒有取得權源；主權被處分了，人權還在。
- 附對手論點與回應、聯合國管道、「領土人民」與「原住民族」的區分、走不通的路線、待查證清單。
- `sources/`：77 份條約、判決、國會紀錄與聯合國文件的文字檔，附原始網址與 sha256。

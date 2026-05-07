# Special Support Day

Dependency-free local MVP.

Open `index.html` in a browser. No npm, pnpm, build step, or internet access is required.

## Purpose
This is a fictional customer-understanding simulation for a PdM. It helps the player feel the trade-offs in a special support teacher's day: child support, parent communication, time pressure, records, and coordination.

## Modes
- ペイン深掘り: product discovery mode for PdMs. After each decision, capture lightweight pain-discovery notes while the scene context is still fresh.
- ABC分析: beginner learning mode for support staff. Sort randomly ordered cards into A/B/C, choose a background hypothesis using related episodes, and select support cards with concepts such as prompts, replacement behavior, reinforcement, and antecedent/consequence adjustment.

## Current Case Library
- 通常級と支援のはざまの一日
- 登校しぶりと家庭の不安
- 保護者との認識ズレ
- 交流学級との連携
- 行動の背景を探る
- ケース会議前夜
- 校外学習前日の準備
- 通級の先生の一日
- 通級と在籍学級の連携
- 時間割のすき間で支える
- 明日の個別課題を選ぶ
- 同じ教材を使い回せない
- 授業後に次回を組み直す
- 年度初めの引継ぎが薄い
- 最初の保護者面談と計画同意
- 交流級担任を巻き込む
- 同じ時間に違う教科が重なる
- 通常級で気になる子に明日試す支援
- 授業開始前のざわつきに対応する

Cases can be filtered by category chips such as `保護者`, `校内連携`, `通級`, `教材・授業`, and `通常級`.

Each case has several scenes, three choices per scene, visible stat changes, per-decision discovery checkpoints, resource-limited choices, accumulated pain tags, a Discovery Map, and a Markdown reflection export.

The Discovery Map groups decision-derived pain signals into categories, drafts need hypotheses, and lists validation questions for the next teacher or internal review conversation.

Resource-limited choices make heavier responses unavailable when remaining time or teacher energy is too low. Choice cards show required resources and actual resource costs as numbers, and the reflection export records which ideal responses became unavailable.

Markdown copy tries the browser Clipboard API first. Because local `file://` execution may block automatic clipboard writes, the app always shows and selects a fallback textarea so the user can copy manually with Cmd+C.

The first ABC case is `対人トラブル × 衝動的に手が出る`.

## Sharing Options
- Easiest: zip this folder and send it. The recipient can unzip and open `index.html`.
- Better for repeated feedback: put this folder in a private GitHub repository and enable GitHub Pages for the project folder.
- Internal-only option: host the folder on an internal static web server. Because this app has no build step and no external dependencies, any basic static hosting should work.

## Important Note
This is not a clinical, legal, or training authority. Scenarios are fictional and should be reviewed with actual teachers before being used as learning material.

Some newer cases are abstracted from a domain-expert document, but the app does not reproduce real cases directly. Public scenarios should remain fictional and anonymized.

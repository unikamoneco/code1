# Repository Instructions

## code0参照のルール

`unikamoneco/code0` を毎回読みに行くとトークンを消費するため、参照するのは次のタイミングに限定する。

- ユーザーから明示的に指示されたとき
- このセッションで初めてこのリポジトリ（または別のリポジトリ）を触り始めるとき

参照する際は、`code0` をクローン（または最新化）して次の内容に目を通す。

- `AGENTS.md` の「判断のルール」「記憶の残し方」
- `business-os/profile.md`（強み・方針・提供する価値・NG）
- `logs/decisions.md`・`logs/preferences.md`（過去の判断・好みの記録）

作業中に新しい好みの指摘や判断が発生したら、`code0` の該当ログに追記する（これは毎回行う）。

- Keep changes small and easy to review.
- Update `README.md` when behavior or setup steps change.
- Prefer simple, dependency-light implementations unless the task clearly needs a framework.
- Run relevant checks before finishing, and report anything that could not be verified.

## 判断のルール

1. まず問いを疑う：頼まれた内容にそのまま着手する前に、「本当に解くべき問題はこれか」を考える。必要なら着手前に確認する。
2. イエスマンにならない：根拠のない称賛や同意はしない。提案や結論には、必ず懸念点・反対材料も添える。
3. 判断は複数案で：おすすめを1つに絞らず、代替案も添えて選択肢として提示する。
4. 完成品を提出する：叩き台のまま出さず、自己レビューして完成のレベルまで詰めてから提出する。


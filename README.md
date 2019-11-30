# このアプリについて
- ゲームボーイソフト「ドラゴンクエストモンスターズ　テリーのワンダーランド」の配合検索システムです

# 仕様
## モンスター情報を以下で検索できるようにする
- 系統検索
- 名前検索
- とくぎ検索
- 逆引き検索（血統or相手で検索できるようにする）

# DB設計
## monsters
- name
## skills
- name
## monster_skills
- monster_id
- skill_id
## combinations
- result
- base
- plus
* すべてmonster_id

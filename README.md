# oishinbo-words

Generate your own wise saying that inspired by Japanese famous comic "Oi-Shinbo"(美味しんぼ).

## Installation

```bash
$ pip install oishinbo-words
```

## Usage

```python
# 山岡士郎
from oishinbo import shiro

shiro.dekisokonai()
# -> この豚バラ煮込みは出来損ないだ、食べられないよ
shiro.dekisokonai("ソースコード")
# -> このソースコードは出来損ないだ、食べられないよ

# 海原雄山
from oishinbo import yuzan

yuzan.kuruma()
# -> 馬鹿どもに車を与えるなっ！
yuzan.kuruma("Vue.js")
# -> 馬鹿どもにVue.jsを与えるなっ！
```

## Supported Characters

- v0.0.1
    - 山岡士郎
    - 海原雄山
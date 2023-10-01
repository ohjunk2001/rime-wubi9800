# rime-wubi9800

一个基于 98 五笔的 rime 输入法配置

# 📖 对 98 五笔方案做了一点改动

- 修改了部分字的编码
- 不再使用简码（一级，二级，三级简码）
- 词组都改成二码一字

## 🌟 码表及改动的编码

码表使用 GB18030 汉字集，包含了 27533 个汉字
具体参见 file 目录下的 GB18030-27533.txt

与原版 98 五笔相比，改动了一部分字的编码

| 字 | 新编码 |
| --- | --- |
| 缶 | tfbj |
| 乀 | nnll |
| 乁 | nnll |
| 粵 | tltn |
| 垂 | tfad |

## 🔥 词组编码说明

- 二字词：每个字前两个编码
- 三字词：每个字前两个编码
- 四字词：每个字前两个编码
- 五字词以上：前四个汉字，每个字前两个编码，最后一个汉字前两个编码

```
花花草草	awawajaj
茉莉花	agajaw
芙蓉出水	agapbmii
区医院	aratbp
工大	aadd
落花有意流水无情	aiawdeujng
工矿	aado
```

## 📑 词库

收集了约 19 万条词组
具体参见 file 目录下的 lexicon.txt
如果需要更多的词库，可以参考我的这个项目 [lexicon](https://github.com/neo742/lexicon)


# 🛠️ rime 配置文件

主要参考了这个 [rime](https://github.com/arzyu/rime-wubi98) 配置

所有的配置文件在目录 rime-config 中

```
pinyin_simp.dict.yaml
pinyin_simp.schema.yaml
wubi98.dict.yaml
wubi98.neo.dict.yaml
wubi98.schema.yaml
```

# 🚀 安装说明

将 rime-config 目录下的文件复制到 rime 用户目录下即可

# 💡 后续完善

💢 注意：这个 rime 方案并不成熟，还有很多可以完善的地方，后续会逐一完善

- 现有的码表，存在一些用不上的异体字和繁体字，可以精简，减少重码
- 自定义短语功能
- 手动造词功能，rime 自带的造词功能不实用
- 颜文字功能
- emoji 功能
- 词库拓展，现有的词库还是不好
- 添加合理的词频
- 合理的快捷键设置

# 🙏 感谢

使用的码表和部分词库来自 [98 资源站](http://98wb.ysepan.com/)

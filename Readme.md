<div align="center">


## resource V0.1.0

## **一个用于存储 [mybot](https://github.com/WriteCode-ChangeWorld/mybot) 机器人:robot:的预设资源仓库**

</div>

</br>

---

## Usage

clone本仓库，并解压目录至`mybot`机器人的`code`目录下

```bash
git clone https://github.com/WriteCode-ChangeWorld/resource
```



**具体目录示例**

```bash
.code
|-- Arsenal
|-- __init__.py
|-- church.py
|-- config.yaml
|-- dynamic_import.py
|-- executor.py
|-- level_manager.py
|-- log
|-- resource		# 解压到此处
|-- workspace		# 该目录为mybot自动生成
```

</br>

---

## 各插件预设资源介绍

| 目录名          | 对应插件                    | 对应插件完成状态   | 对应路径                           | 描述                                   |
| --------------- | --------------------------- | ------------------ | ---------------------------------- | -------------------------------------- |
| Blhx_Build_Pool | 碧蓝航线-模拟建造插件(十连) | **已完成**         | ./code/Arsenal/bot_blhx_build_pool | 碧蓝航线十连建造所需的数据及素材       |
| Blhx_Secretary  | 碧蓝航线-随机秘书舰抽取     | 作用不大，暂停维护 | ./code/Arsenal/bot_blhx_prediction |                                        |
| Day_Illust      | N/A                         | N/A                | N/A                                |                                        |
| Phantom_Img     | 随机涩图插件                | 待完成             | ./code/Arsenal/bot_color_img       | 随机涩图—幻影坦克模式生成的demo图片    |
| Pokenman        | 宝可梦杂交插件              | 待完成             | ./code/Arsenal/bot_pokenman        | 素材                                   |
| Random_Text     | N/A                         | N/A                | N/A                                |                                        |
| temp            | mybot默认配置文件模板       |                    | ./code/config.yaml                 |                                        |
| WhatAnime       | 番剧搜索插件                | 待完成             | ./code/Arsenal/bot_whatanime       | 番剧搜索的缓存图片、番剧搜索动图的缓存 |
| ...             | ...                         |                    | ...                                | ...                                    |


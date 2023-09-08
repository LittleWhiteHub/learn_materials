
# learn_materials

本项目主要用于python学习，请勿非法使用脚本，下载后请于24小时内删除

# 大家好 我是LittleWhiteHub! 👋

普普通通打工人，热爱研究脚本

## 投稿及问题说明

如果你需要编写脚本、想法意见或者任何问题，请在
https://github.com/LittleWhiteHub/learn_materials/issues
进行反馈说明


## 学习研究方向

- 小程序脚本学习

- app脚本学习（部分不需要逆向的app，后期会攻克需要逆向带来的困扰）

- python脚本运行小程序或者app

## 拉库命令

```bash
  ql repo https://ghproxy.com/https://github.com/LittleWhiteHub/learn_materials.git
```
    
## 自用青龙docker搭建命令

```bash
  docker run -dit \
   -v $PWD/ql/config:/ql/config \
   -v $PWD/ql/log:/ql/log \
   -v $PWD/ql/db:/ql/db \
   -v $PWD/ql/repo:/ql/repo \
   -v $PWD/ql/raw:/ql/raw \
   -v $PWD/ql/scripts:/ql/scripts \
   -v $PWD/ql/deps:/ql/deps \
   -v $PWD/ql/.pnpm-store:/ql/.pnpm-store \
   -p 5700:5700 \
   --name qinglong \
   --hostname qinglong \
   --restart unless-stopped \
   whyour/qinglong:last
```


## 免责声明

仓库内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。

LittleWhiteHub对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, 对于由此引起的任何隐私泄漏或其他后果概不负责.

如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本.

任何以任何方式查看此项目的人或直接或间接使用该python项目的任何脚本的使用者都应仔细阅读此声明。 
LittleWhiteHub保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或python项目的规则，则视为您已接受此免责声明.

您必须在下载后的24小时内从计算机或手机中完全删除以上内容.严禁产生利益链
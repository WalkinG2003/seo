## 帖子转载：https://seotoprofit.com/t/topic/4309
## 原文链接：https://seotoprofit.com/t/topic/4309


:rocket: 教你从零克隆群组管理机器人（超详细图文教程）
本期内容带大家一起 克隆一个属于自己的 Telegram 群组管理机器人 :robot:
包含：

如何通过 @BotFather 创建机器人
如何通过 GroupHelp 克隆机器人并去掉别人的广告
如何设置 群组 / 频道管理员权限
如何开通 专业版 / 豪华版，解锁私聊欢迎消息等高级功能
只要按步骤操作，就能做出一个专业、美观、自动化的群管机器人！

:puzzle_piece: 第一部分：创建机器人（BotFather）
首先前往 @BotFather 创建一个新的机器人，把基础设置都操作一下，包括头像、简介、描述等。
主要目的是取得机器人的 Token :key:

image
image
771×931 45 KB

image
image
771×931 49.3 KB
头像、简介、描述这些可以之后再调整，没有影响。关键是获取 Token：

image
image
771×931 45 KB

image
image
771×925 53.4 KB
复制 Token 并发送给 @GroupHelpBot，出现“正在工作中”即可说明克隆成功：

image
image
771×933 58 KB

image
image
771×928 123 KB
“命令同步”表示当前你的机器人与模板同步，你也可以后续自行修改命令。

image
image
771×894 45.3 KB
回到自己的机器人，输入 /start 出现群管菜单，就是克隆成功的标志 :tada:
不过此时机器人的界面仍带有 GroupHelp 自带广告，后面会教你彻底去掉。

:hammer_and_wrench: 第二部分：设置机器人管理员权限
为了让机器人在群或频道内正常管理，需要给它设置足够的管理员权限。

image
image
739×678 31.7 KB

image
image
771×841 54.4 KB

image
image
771×860 52 KB

image
image
771×866 32.4 KB
如果没有提前设置权限，添加机器人时会出现如下提示 :down_arrow:

image
image
818×793 61.7 KB

image
image
562×547 23 KB

image
image
637×334 32.7 KB
左边是群组权限，右边是频道权限 :down_arrow:
建议全部开启 :check_mark:

image
image
720×859 32.4 KB

image
image
771×866 39.7 KB

image
image
771×865 38.8 KB
全部勾选后效果如下：

image
image
737×806 58.2 KB

image
image
755×823 63 KB

image
image
878×918 61.1 KB
成功加管理员后，机器人能自动发送消息并正常工作：

image
image
698×893 72.8 KB

image
image
571×231 20 KB
:gem_stone: 第三部分：开通 Group Help 专业版（去广告）
为了去除借用模板带来的广告，我们需要开通专业版。

image
image
698×893 72.8 KB
当时的价格如下（可能变动）：

image
image
698×777 40.7 KB

image
image
698×960 52.2 KB
进入机器人 /start → 群组设置 → 管理群组：

image
image
698×793 45.1 KB

image
image
698×779 32.1 KB
进入设置后，点“其他 → 权限 → 自定义角色”，即可看到专业版购买入口：

image
image
698×892 60.1 KB

image
image
698×895 48.9 KB
点击购买后会跳转至 @GHDonateBot：

image
image
698×774 43.6 KB
当前价格 3.0 → 支持 5 个群组永久专业版：

image
image
659×648 34.7 KB
强烈建议一步到位开通 豪华版（Deluxe）
我后来因为需要增加群组数量又补买了一次，不如直接一次性搞定：

image
image
771×750 38.4 KB
:wrapped_gift: 专业版可解锁功能（强烈推荐）
主要包括：

反色情过滤
无需「/」即可使用个人命令
无头像惩罚机制
自动删除指定类型消息
群组标签助手 @Tags
最多 3 条定时消息（支持 1~5 分钟短间隔）
防快速加退
个人命令联动 cmd: 功能
编辑克隆机器人启动消息（去广告最重要）
续费界面说明：

image
image
771×802 46.4 KB

image
image
771×755 43.2 KB

image
image
771×750 38.8 KB
购买总价示例：

image
image
771×750 38.8 KB
购买入口示例：

image
image
2560×1398 140 KB
也可使用信用卡：

image
image
771×791 38.5 KB

image
image
771×933 56.1 KB

image
image
837×556 35.7 KB

image
image
700×794 29.7 KB

image
image
751×527 32.8 KB

image
image
694×505 27.9 KB
:star: 第四部分：设置自定义 /start（去广告最关键）
购买后，执行以下命令：

/prostart （激活）
/setstart 文案内容
/getstart （查看当前文案）
/setb 按钮设置
/getb 查看按钮
/unprostart （关闭自定义）
image
image
771×750 118 KB

image
image
771×750 23.9 KB
示例（美观文案）：

/setstart 您好，%mention%（%id%）欢迎使用「柬埔寨 - 群组管理机器人」🎉

👉 <a href="https://t.me/chumaxy">西港出码・金边出码・木牌出码｜安全快速，一键联系</a>
👉 <a href="https://seotoprofit.com">seoToProfit｜顶级论坛：找人、找资源、找合作，一站式直达🔥</a>
按钮格式示例：

🇰🇭 柬埔寨同城群 - https://t.me/xgcma2 && 🌐 seoToProfit - https://seotoprofit.com/
🔐 西港安全出码 - https://t.me/xgcma1 && 💬 出码客服 - https://t.me/chumaxy
🤖 添加我到群组 - https://t.me/CTambodiaBot?startgroup=start
效果如下：

image
image
758×525 32.1 KB
:incoming_envelope: 第五部分：加入群组后自动私信欢迎
关键前提有 三个：

:one: 开启群组 新成员审核
:two: 在机器人里设置 欢迎消息
:three: 审核方式调整为 自动批准（并选择“发送到私聊”）

image
image
771×863 58.6 KB
设置示例：

image
image
771×933 42.8 KB

image
image
771×930 93.2 KB

image
image
771×856 64.5 KB
加入群测试效果：

image
image
771×674 32.3 KB
优化文本示例：

image
image
771×865 52.8 KB
记得打开 “每次发送”，不要只选“首次加入”：

image
image
771×862 42.6 KB
image
image
1200×930 94.3 KB

image
image
1200×929 105 KB
:glowing_star: 克隆机器人的意义
克隆自己的机器人可以实现：

私人品牌推广
去除原机器人广告
当别人使用你的机器人时，你的曝光率也会上升
形成群裂变与广告扩散效果
打造专属的群管理体系

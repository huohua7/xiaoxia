# Banned Expressions List

以下表达已被识别为高频AI生成特征。writer 在写作时主动规避，reviewer 在审核时兜底检查。

## 英文禁用表达

### 开头/过渡类
- "Ever since I was a child"
- "In today's rapidly changing world"
- "As someone who has always been passionate about"
- "My journey began when"
- "This experience was a turning point in my life"
- "It was then that I realized"
- "This transformative experience"
- "Looking back, I can see that"

### 能力/品质声明类
- "ignited my passion for"
- "deepened my understanding of"
- "I am a firm believer that"
- "I thrive in environments where"
- "My unique combination of skills"
- "I bring a diverse perspective"
- "profoundly changed my perspective"
- "solidified my commitment to"
- "honed my skills in"

### 结尾/收束类
- "I am eager to contribute to"
- "I am confident that"
- "I look forward to the opportunity"
- "I am excited to bring my"
- "This program aligns perfectly with"
- "[School] is the ideal place for me to"
- "I am committed to leveraging"

### 连接词滥用
连续使用以下任意两个即触发修改：
Furthermore, Moreover, Additionally, In addition, Subsequently, Consequently

## 中文禁用表达（如文书为中文）

- "怀着对XX的热爱"
- "这段经历让我深刻认识到"
- "我坚信"
- "在全球化的今天"
- "我有幸参与了"
- "贵校/贵项目以其卓越的XX享誉世界"
- "我期待在XX的平台上"
- "带着这份初心"

## 结构模式禁用

- 每段都以"During my time at [机构名]"开头
- 每段都以"This experience taught me that..."结尾
- 三段式"挑战→行动→成果"连续使用超过两次
- 结尾段机械回扣开头的意象或措辞（"回到文章开头的那个实验室..."）

## 维护说明

当 reviewer 在审核中发现新的疑似AI套话模式时，建议 coordinator 将其追加到本清单。
清单应随LLM生成特征的演变定期更新。
# Minecraft 模组翻译：《积累》（内容需要重新分配以系统化）

## 前言

本文是基础教程《Minecraft 模组翻译：从入门到开发》的进阶教程之一。

本篇教程不再关注翻译投递的问题，这些问题在基础教程中已经得到了需要知道的大部分解答，想要进一步掌握 Git 相关内容则可以参阅《Minecraft 模组翻译：Git 进阶操作》。本文侧重于具体的翻译相关内容。但注意，此“翻译相关”教程并不打算教你如何翻译一个词或者一句话（虽然还是被迫教了），这些技能应该是你在英语课堂中而不是我们这训练出来的，我们也不会提供相应的配套练习。该“翻译相关”，指的是在翻译 Minecraft 模组及其他 Minecraft 相关文本时才可能出现的额外问题。这部分的问题及其答案，只有对此方面已有较多接触的翻译工才会知晓。尽管对于这些问题本篇教程会给出一定回答，但本篇教程并无可能穷尽所有这方面会出现的问题，也不能保证文中答案一定符合语境或惯例或通用处理方式。有什么问题、作什么处理、选什么答案，都是进入到具体的翻译过程中才能解答的问题，脱离了翻译过程的翻译理论，总是难以真正解决实际问题的。所以也请参阅本篇教程的各位，对本文可能包括的问题作补充，共同进步。感激不尽。

虽然本文并不以通用翻译指导为重点，但考虑到一般的翻译人员可能并不会刻意查找细节性的指导，本文也会包含一些问题出现频率较高、应用较广的说明。

我（轩辕）推荐你在十分确定时以 [“忽略所有规则”](https://zh.wikipedia.org/w/index.php?title=Wikipedia:IAR) 作为自己处理问题的态度。

来自 [裂文唬客](https://github.com/LWHK)，本文作者：[清秋](https://github.com/TUsama)，[轩辕](https://github.com/WuzgXY-GitHub)

## 词语翻译

词语翻译从来都是翻译中的重头戏，在模组翻译中，有些词是原版已有的，有些词是遵循常用意而使用的，有些词则是作者自造的。但无论如何，你都得记住这一点：词语翻译从来都是要求“信”字打头，“达”与“雅”总是靠后的。有时候你可能想出一个很通顺或者雅致的词语，但是在词义表达上却总是缺一层意思。那么不要犹豫，选择那个较为能够体现出原文的词语，作为最终的翻译。

但是有的时候，作者的原文甚至写得不如你好——我是说，可能作者在为物品或者方块取名时，一下子没想起好的词，确切的词，又或者原名取得和游戏内的对象差了十万八千里，你完全无法理解这个词是怎么来的。在这种情况下，你可以先去咨询作者，看看作者有没有较为满意的解释，如果有，那么你就照着它的来，如果没有那你还可以建议他改名。

我在这里不会展开讲太多这方面的细节，因为这些细节会在魔法类模组以及科技类模组中不尽相同，这些需要你去摸索，甚至是没有完全确定的，可以循规蹈矩的操作细节的，这些更多的取决于译者自己的翻译习惯，所以细节上千姿百态也就不足为奇了。但是无论如何，请记住一点：我们是要为玩家，为社区，为作者负责，在做一些比较重要的决定的时候，请先想一想这一点，再去做决断。

### 所谓“定番”与“非定番”词语

”定番“，严格来说，在这里用这个词是不合适的，因为这个词的本意与翻译并无交集。我将这个词的词义引申为”那些翻译已经完全固定了的词“。这些词，毫无疑问，指的就是原版的词汇。所有的原版词汇，都可以在 [Minecraft Wiki:译名标准化](https://minecraft-zh.gamepedia.com/Minecraft_Wiki:%E8%AF%91%E5%90%8D%E6%A0%87%E5%87%86%E5%8C%96)这一页面上查看到。任何尝试进行模组翻译的翻译工，都得首先知晓原版中使用了哪些英文词汇/词组，并且这些词汇/词组对应了中文中的哪些翻译。例如，经典的 Projectile 一词，应该翻译为”弹射物“，如果你在所有的地方都正确翻译了这一词，那么玩家的相关疑虑便会减轻很多，例如，如果你将某个魔法类模组的魔法的文本介绍中出现的 Projectile 一词，正确翻译为了”弹射物“，那么，玩家就不会发问：这个魔法发出的飞行物所造成的伤害，能不能被”弹射物保护“附魔影响？在正确的翻译情景中，这样的问题是不会从正常人的嘴里问出来的：因为弹射物保护能够降低弹射物的伤害，这是**天经地义**的。当然，不正常的人需要被排除。

还有一个翻译者经常忽略的原版词汇，那便是所有的“颜色”，对应原版颜色的装饰性方块，在翻译时就不要搞出“姹紫”“嫣红”“嫩橙”这种乱七八糟的翻译了。汉语中对于颜色的描绘是相当多的，如果你不想在玩模组的时候，一个颜色有数十个翻译，那我建议你乖乖将 red 翻译为“红色”，pink 就翻译为“粉红色”。

而那些“非定番”的词汇，便是指所有非原版词汇的词语。这些词语我们会在接下来的章节中，以更为细分的形式进行讨论，此处按下不表。

#### 自造词语

自造词汇，作为非定番词汇中的占比较小的词汇，却在各种模组中有着一席之地。这就坑害了广大的翻译者。因为毋庸置疑，自造词汇的翻译是无法在词典上找到的，你必须正确的拆分出自造词汇的各个意义单元，将其组合起来，才能领会到作者想要表达的正确意思。（业余处理，需要重新考虑用语）

现举一例第一段中的例子（本方法仅为示例，所提供的方法仅供参考；除非询问作者，你无法确定自己的猜测是否正确）：

困扰诸多星辉玩家的“法斯刻”、“多米刻”、“艾克斯”三个词到底是什么？

这三个词的原文为：

1. Fosic
2. Domic
3. Ichosic

原译者直接将其音译，且这么长时间都无人来探究这些词语背后作者暗藏的真正意思，实在是令人扼腕叹息。

这些词语在词典上直接搜是搜不到。那么，你必须对其进行适当的拆词，方可找到词语中隐藏的意义。有一定英语水平的人都知道，-ic 作为形容词常见的后缀，说明了这三个词应该是形容词。确定了词尾后，我们将词尾先移开，看看剩下的部分是否有意义：

1. Fos
2. Dom
3. Icho

还是没有实际的意义，但是考虑到英语单词在加上词尾时，往往会先削去一两个结尾的字母，再添加相应的词尾。我们可以考虑再在此基础上做字母变动。在这种情况下，我们可以将这些剩余部分写入词典中，检查词典弹出的备选项，看看有无单词是比较贴合游戏中的实际作用的。

我们能够查到：

1. Foci
2. Dome
3. Ichor

这三个词，较之原来的形式，都发生了部分的字母变动，或增或减，但是这些增减是有着游戏内内容的依据的。以下是论证（引号乱七八糟）：

1. 对于词”Foci“，选择它是因为它有”集中“之意，结合游戏中的”法斯刻之域“（此处也是音译）的设定，我们立刻可以意识到两者之间的意义关联：”法斯刻之域“乃是星能汇聚之地，恰有 Foci 的“集中”之意在里头。这可不是巧合，很有可能是作者就是沿着这个词创造出了“Fosic”这一词。此时，我们已经可以将这个“Fosic”做“Foci”来看待，结合星辉的设定，在 1.16 的星辉魔法中 ，我将其定为“汇星”。
2. 对于词“Dome”，与物品的效果完美贴合，使用了“多米刻共振器”后，可以显示出“效应放大器”（在最新版中也改了名字，为“仪式基座”，此处乃是最最基本的误译）的效果范围，动画上乃是一片区域。所以此处翻译定为“穹域”。
3. 对于词“Ichor”，与“纳耳狂曼喷口”（翻译亦有变动）的效果完美重合，此处定为“液华”。

以上 2、3 两个解释，均出自于 [Ex](https://github.com/Determancer)，我们 [LWHK](https://lwhk.github.io) 的中坚人物，在此十分感谢他的工作。

#### 老词新意

#### 对哏的翻译

## 长文本翻译

### 翻译原则的优先级

### 翻译的整体风格倾向

翻译腔（部分文化环境下翻译腔也是可取的，如日语 - 轻小说）

## 其他细节

### 一般语文问题

本段中标题全部为错误例子，错误之处以**粗体**标明。

1. 本模组添加了一些物品、方块<b>、以及</b>生物。

    顿号不能与并列性连词同时使用。本例中并列的三个语素从`物品`、`方块`和`生物`变成了`物品`、`方块`和`以及生物`，这显然是错误的。

    正确版本：

    `本模组添加了一些物品、方块、生物。`（语法上没问题，但本例中略显生硬）

    `本模组添加了一些物品、方块以及生物。`

2. 你可以选择生存<b>/或</b>创造模式。

    斜杠自身已经有“或”的含义了，不能与同类连词同时使用。有些原文包含 `/or`，此时应视情况在翻译中应用合理的用法，而不应延续原文的错误。

    正确版本：

    `你可以选择生存/创造模式。`

    `你可以选择生存或创造模式。`

3. 我想知道<b>为什么</b>这模组没汉化<b>？</b>

    `为什么`等特殊疑问词引导的从句不能与问号同时使用。

    正确版本：

    `我想知道为什么这模组没汉化。`

    `为什么这模组没汉化？`

4. 我<b>是</b>男。

    多数人看到标题都能一眼发现问题，少了一个“的”，对吧？那么我们来换一个更长的例子（本例）。

    ``本模组是在区块更新时使用动态渲染，并在已加载区块中使用静态渲染。`

    你可能觉得这个句子没啥问题，所以我们先放正确版本：

    `本模组是在区块更新时使用动态渲染，并在已加载区块中使用静态渲染的。`（本例中略显生硬）

    `本模组在区块更新时使用动态渲染，并在已加载区块中使用静态渲染。`

    看出问题了吗？本段标题中的问题是谓语为`是`时，形容词缺少助词`的`的问题，`男`是一个形容词，而中文中我们通过添加`的`可以将之转换为名词（如`快看那边那个男的`），也可以使之符合这种定语的形式规则。名词与形容词皆可得到合理解释，此处不应过度纠结标题中`男的`二字的词性。本例亦同，正确版本的第一句中`在区块更新时使用动态渲染，并在已加载区块中使用静态渲染的`是宾/定语，可以在谓语`是`后使用，构成完整的句子；第二句可以简化为`本模组使用渲染`，也即一个简单的主谓宾结构语句，其他部分都作修饰用。

5. 本模组的矿脉生成<b>频率多</b>。

    不是大问题，但还应注意词语搭配得当，`频率`只能`高`不能`多`。

    正确版本：

    `本模组的矿脉生成频率高。`

6. <b>为什么</b>你崩溃<b>的原因</b><b>是因为</b>你没装前置。

    同义词多次出现。

    正确版本：

    `你崩溃的原因是你没装前置。`

    `你崩溃是因为你没装前置。`

    `你没装前置。`（玩笑）

7. 这个模组的<b>重置版</b>需要<b>重头</b>开发。

    格雷错被字。`重置`一词自身不喊错别字，但用在哲理并不正确，应注意去分`重置`和`重制`。类似的栗子很多，比如`奔溃`、`客服端`、`虚似机`，等等。如果你连这鞋问题都看不出来，那请在进一步烦译前提高自己打认字数。

    正确版本：

    `这个模组的重制版需要从头开发。`
    
8. `其`是一位父亲的儿子。

    `其`这个字比较特殊，它不能作为主语或宾语单独出现，但可以作定语或作主语或宾语且后接补语。
    
    正确版本：
    
    `他是一位父亲的儿子。`
    
    `其身份是一位父亲的儿子。`（对原句略有修改，仅供语法示意）
    
#### 排版

*WIP*

例仍皆错/不推荐；粗体标出错误

1. 1000m**b**/t -> 1000 mB/t

2. Git**h**ub用户sparanoid -> GitHub 用户 sparanoid（推荐）

3. 全角标点符号（联系国标、《夹用英文的中文文本的（草案）》）；可参考 WP；省略号（……好丨......差丨...愚蠢）

### 游戏用语问题

#### 各类定番术语

如上文所言，原版翻译是模组翻译工必不可少的基本功，多看多练，才能在翻译时记住这些词汇，至少能做到认出这个词翻译的确定性，不会自己安一个新的翻译上去。

以下列举出了一些常见的，易被翻译错误的原版词汇及基础模组术语：

（轩辕你来吧）（我还没来）（字幕）

不同模组类别的译名（可参考各模组的译名表）：

#### 学术词语

CNKI

可以尝试以 [《地质学报》的矿物名中英对照表](https://wuzgxy-github.github.io/) 作为参考，仍需注意统一性

#### 键鼠操作称呼问题

*WIP*

具体描述各种键鼠操作的正确称呼。

（非触屏情况下）点击与单击

左击/键与单击

右键与右击

点两下与双击

按与摁

Shift+单击与按住 Shift 单击

Shift 和 sneak 的区别

左 Ctrl

### 革新的时机与注意事项

### 对哏/迷因的翻译

与某圈主题并不重合的模组化用了大量该圈内容

Suzune Maiki：
应当翻作日语，尽可能保留作者「想向圈内人传达这个梗」的想法

清秋：
除了能两全的，应当保留原文，反正我不翻就和我没关系（WuzgXY：最后这句显然是不负责任的说法，你应该说出于各种考虑保留）

CrmP：
所有的都应当翻作中文，因为翻译首先要合理达意，圈外人相比圈内人又多了太多，圈内人照顾不到就算了

WuzgXY：
因为该圈内容自身与模组化用处直接挂钩，本就很难照顾到圈外人，故不能两全时应保留原文

# game_engine_share
game_engine_share

[describe](http://chengyuanheng.github.io/game_engine_share)

[image](http://slides.com/cckkll/you#/)

===

1.游戏引擎是什么
百度百科： 游戏引擎是指一些已编写好的可编辑电脑游戏系统或者一些交互式实时图像应用程序的🐴核心组件🐴。
         这些系统为游戏设计者提供各种编写游戏所需的各种工具，其目的在于让游戏设计者能容易和快速
         地做出游戏程式而🐴不用由零开始🐴。大部分都支持多种操作平台，如Linux、Mac OS X、微软Windows。

         游戏引擎包含以下系统：
            渲染引擎：网页浏览器的排版引擎也被称为页面渲染引擎，它负责取得网页的内容（HTML、XML、图象等等）、
                    整理信息（例如加入CSS等），以及计算网页的显示方式然后会输出至显示器或打印机。
                    所有网页浏览器、电子邮件客户端以及其它需要编辑、显示网络内容的应用程序都需要排版引擎。
            物理引擎：物理引擎通过为刚性物体赋予真实的物理属性的方式来计算运动、旋转和碰撞反映。
                    为每个游戏使用物理引擎并不是完全必要的—简单的“牛顿”物理（比如加速和减速）
                    也可以在一定程度上通过编程或编写脚本来实现。
                    然而，当游戏需要比较复杂的物体碰撞、滚动、滑动或者弹跳的时候（比如赛车类游戏或者保龄球游戏），
                    通过编程的方法就比较困难了。
            碰撞检测系统：
            音效：
            脚本引擎：所谓脚本引擎，就是一个计算机编程语言的解释器，如用于建网站的asp、php等，
                    它的功能是解释执行用户的程序文本，将它译成计算机能执行的机器代码，完成一系列的功能。
                    早期的桌面数据库如dbaseIII、foxbase等也属于脚本型编程语言.
            电脑动画：
            人工智能：
            网络引擎：
            场景管理：

         对于游戏开发者来说，引擎可以理解为🐴一个封装好的盒子🐴，它的功能是🐴提供调用接口🐴，
         好让一些复杂的事情通过这个盒子之后变的简单。 举个例子，我们要在计算机上渲染一个3D的场景，
         而从实际上来说，显示在你的电脑屏幕上的只是一张带有深度感觉的2D图片。对于游戏场景来说是一样的。
         首先美术创建了许多3D模型，而这些3D模型分解起来就是许多的三角形包围出来的密封体。然后在这模型基础上，
         美术绘制了一层叫做贴图的东西，这东西很像人的皮肤，于是……一个模型就诞生了。

2. 游戏引擎发展史

    游戏引擎（Game Engine）是什么？大多数人给出的解释都是基于engine的英文翻译，
    将游戏引擎等同于汽车中的引擎（发动机），
    再好一些的解释成动力，这些解释都对，但是动力只说并不全面，不能完整反映出游戏引擎在游戏中的作用与地位。

    先举一个简单例子，在某游戏中的一个场景中，玩家控制的角色躲藏在屋子里，敌人正在屋子外面搜索玩家。
    突然，玩家控制的是一个穿迷彩服的士兵，突然碰倒了桌子上的一个杯子，杯子坠地发出破碎声，
    敌人在听到屋子里的声音之后聚集到玩家所在位置，玩家开枪射击敌人，子弹引爆了周围的易燃物，
    产生爆炸效果。在这个简单而常见的过程中，游戏引擎便在后台起着作用，控制着游戏中的一举一动。

    可以说，🐴游戏引擎虽然有着“动力（Engine）”之名，但是其实际上却是行“大脑（brain）”之实🐴

    http://edu.gamfe.com/tutor/d/41955.html

  诞生（1992年~1993年）
      3D Realms公司/Apogee公司-》2兆多的小游戏——《德军司令部》（Wolfenstein 3D） 第一人称射击游戏
      更重要的是，🐴它在X轴和Y轴的基础上增加了一根Z轴🐴，在由宽度和高度构成的平面上增加了一个向前向后的纵深空间，
      这根Z轴对那些看惯了2D游戏的玩家造成的巨大冲击可想而知。

      引擎诞生初期的另一部重要游戏同样是出自id Software公司的一款非常成功的第一人称射击游戏——《毁灭战士》（Doom）
      由于Doom引擎本质上依然是二维的，因此可以做到🐴同时在屏幕上显示大量角色而不影响游戏的运行速度🐴，
      这一特点为游戏创造出了一种疯狂刺激的动作风格，在这方面迄今为止大约只有《英雄萨姆》（Serious Sam）系列能与之相比，
      除此之外还没有哪款3D引擎能在大批敌人向你涌来的时候依然保持游戏的流畅，
      不过更值得纪念的是，🐴Doom引擎是第一个被用于授权的引擎🐴  -> 投影者,异教徒,毁灭巫师

  转变(1994年~1997年）
    肯·西尔弗曼于1994年为3D Realms公司开发的Build引擎是一个重要的里程碑
    Build引擎的🐴授权业务大约🐴为3D Realms公司带来了一百多万美元的额外收入，
    3D Realms公司也由此而成为了引擎授权市场上的第一个“暴发户”。不过从总体来看，
    Build引擎🐴并没有为3D引擎的发展带来任何质的变化🐴，

    突破的任务最终由id Software公司的《雷神之锤》（Quake）完成了。
    Quake引擎是当时🐴第一款完全支持多边形模型、动画和粒子特效的真正意义上的3D引擎🐴，而不是Doom、Build那样的2.5D引擎,
    此外Quake引擎首开连线游戏的先河 一年之后，id Software公司推出《雷神之锤2》，一举确定了自己在3D引擎市场上的霸主地位
    Quake II引擎独霸整个引擎市场的时候(授权)

    Unreal引擎:🐴使用最广的一款引擎🐴: Unreal引擎的应用范围🐴不限于游戏制作，还涵盖了教育、建筑等其它领域🐴:
      Digital Design公司曾与联合国教科文组织的世界文化遗产分部合作: 巴黎圣母院的内部虚拟演示
      Zen Tao公司: 为空手道选手制作过武术训练软件
      另一家软件开发商Vito Miliano公司: 开发了一套名为“Unrealty”的建筑设计软件，用于房地产的演示

  革命(1998年~2000年): 例如，所有采用Doom引擎制作的游戏，无论是《异教徒》还是《毁灭巫师》，都有着相似的内容，
      甚至连情节设定都如出一辙。玩家开始对端着枪跑来跑去的单调模式感到厌倦，开发者们不得不从其它方面寻求突破，
      由此掀起了第一人称射击游戏的一个新的高潮。 🐴人工智能🐴

      两部划时代的作品同时出现在1998年: Valve公司的《半条命》（Half-Life）,  Quake和Quake II引擎的混合体
            特性：一是脚本序列技术，这一技术可以令游戏以合乎情理的节奏通过触动事件的方式让玩家真实地体验到情节的发展
            第二个特性是对人工智能引擎的改进，敌人的行动与以往相比明显有了更多的狡诈，不再是单纯地扑向枪口

        LookingGlass工作室的《神偷：暗黑计划》（Thief：The Dark Project）
          在人工智能方面真正取得突破的游戏是Looking Glass工作室的《神偷：暗黑计划》

      从2000年开始3D引擎朝着两个不同的方向分化，一是如《半条命》、《神偷》和《杀出重围》
      那样通过融入更多的叙事成分和角色扮演成分以及加强游戏的人工智能来提高游戏的可玩性，

      二是朝着纯粹的🐴网络模式🐴发展 他们意识到与人斗才是其乐无穷，于是在Quake II出色的图像引擎的基础上加入更多的网络成分，
      破天荒推出了一款完全没有单人过关模式的纯粹的网络游戏——《雷神之锤3竞技场》（Quake III Arena），
      它与Epic公司稍后推出的《虚幻竞技场》（Unreal Tournament）一同成为引擎发展史上的一个转折点。

  未来（2001年~）
    🐴Quake III和Unreal Tournament等现成引擎🐴：   《星际迷航深度空间九：坠落》、《重返德军总部》和《荣誉勋章：盟军进攻》

    🐴自己开发的引擎🐴：网络射击游戏《部落2》（Tribes 2）、第一人称射击游戏《马克思佩恩》、《红色派系》（Red Faction）
                  和《英雄萨姆》等。
      《部落2》采用的是V12引擎  但开发者为它制定的许可模式却相当新颖，你只需花上100美元就可以获得引擎的使用权
              一系列规定相当苛刻   不能把该引擎用于为其它游戏发行商、
              其它商业游戏站点等竞争对手制作游戏开发出来的游戏必须在发行前交给GarageGames公司（V12引擎的所有者），
              不能交给任何第三方，GarageGames公司将拥有这些游戏五年的独家发行权等

      《马克思佩恩》采用的是MAX-FX引擎  支持辐射光影渲染技术（Radiosity Lighting）的引擎
          连🐴子弹的飞行轨迹都可以看得一清二楚🐴。MAX-FX引擎的问世把游戏的🐴视觉效果推向了一个新的高峰🐴。

      《红色派系》采用的是Geo-Mod引擎  🐴第一款可任意改变几何体形状的3D引擎🐴  你可以使用武器在墙壁、
            建筑物或任何坚固的物体上炸开一个缺口，穿墙而过，或者在平地上炸出一个弹坑躲进去

              Geo-Mod引擎的另一个特点是🐴高超的人工智能🐴  敌人不仅仅是在看见同伴的尸体或听见爆炸声后才会做出反应，
              当他们发现你留在周围物体上的痕迹如弹孔时也会警觉起来，
              他们懂得远离那些可能对自己造成伤害而自己又无法做出还击的场合，受伤的时候他们会没命地逃跑，
              而不会冒着生命危险继续作战

      《英雄萨姆》Serious引擎  特点在于🐴异常强大的渲染能力🐴 面对大批涌来的敌人和一望无际的开阔场景，
            你丝毫不会感觉到画面的停滞

    《激战海陆空》Unity3D游戏引擎技术  🐴创造性地解决了多人大规模同时在线战斗这一世界性难题🐴，
      使“把第一人称射击游戏放入大型网络环境中”的构想成为可能，
      也成为了迄今为止世界上唯一一款海陆空全实景全拟真立体模拟战争游戏。
      🐴游戏采用的Unity3D游戏引擎技术，全世界独此一家🐴

  最后需要指出的是，许多优秀的游戏开发者正在🐴退出游戏开发市场，转而进入引擎授权市场🐴，
  仅靠开发引擎吃饭，这是个危险的信号。尽管引擎的不断进化使游戏的技术含量越来越高，
  但最终决定一款游戏是否优秀的因素在于使用技术的人而不是技术本身。
  如前所述，引擎相当于游戏的框架，框架打好后，你只需往里填充内容即可，在这里，框架只是提供了一种可能性，
  游戏的精彩与否取决于内容如何而非框架如何。正如《无人永生》开发小组所说：“所有问题最终都会归结为一点——你的游戏是否好玩。

3. 市场占有率比较大的10款游戏引擎

   随着手游的快速增长和游戏业的发展，选择合适的引擎已经变得越来越困难。很明显，对于开发商们来说，
   有着成功游戏开发历史的引擎是首选，但随着家用机与手游设备的变化，我们选择游戏研发引擎时必须从多个方面分析，
   以下是开发商们不可不知的10款引擎：

　　Unity3D
      网页游戏:
      坦克英雄（网页游戏） 皇牌海战 🐴新仙剑Online🐴 蒸汽之城 🐴绝代双骄🐴 Touch 纵横无双 将魂三国 天神传
      QQ乐团 北欧英灵传 星之战记 骑士的远征(已停止运营) 萌战记 推倒Online 格子RPG 图腾王 争锋OnLine
      喷喷战机(已停止运营) 魔偶给我冲 猪仙 木乃伊OL (The Mummy Online) 魔晶星球 将神 天宠岛 Kartuga
      极限摩托车2 (Trial Xtreme 2) 枪战世界（OffensiveCombat） 梦幻国度2 UberStrike Kartuga Robocraft

      手机游戏:
      失落帝国 战舰少女 地牢女王[1]  MemoLine! 🐴炉石传说🐴 酷酷爱魔兽 捣蛋猪(Bad Piggies) 神庙逃亡2（Temple Run 2）
      武士2: 复仇 亡灵杀手：夏侯惇 蛮王记 极限摩托车2 (Trial Xtreme 2) 🐴神庙逃亡：勇敢传说(Temple Run:Brave)🐴
      Bladeslinger 火车危机(Train Crisis) 血色屋顶(Blood Roofs) 猎鹿人(Deer Hunter Reloaded)
      果冻防御(Jelly Defense) ChopChop Tennis 9号计划之地下雅利安 暗影之枪：死亡禁地 （Shadowgun: DeadZone)
      Komodo Crunchtime:Ultimate Sup The Drowning The Room Pocket 三国之杀场 王者之剑 Rochard
      Momonga弹珠冒险记 Tap Sonic Star 死亡扳机 (DEAD TRIGGER) 公路战士(Road Warrior) 极速飞盘 Frisbee Forever
      口袋RPG (Pocket RPG) 机器人大战 (Roboto) 绝命武装（Bravo Force：Last Stand） 阿尔龙：剑影 ( Aralon：Sword and Shad)
      街头摔跤 ( Street Wrestler ) 缪斯（M.U.S.E.） 疯狂的公牛（Bull Dozer） year walk Jack Lumber
      神庙逃亡：魔境仙踪（Temple Run Oz 血之荣耀：传奇 ( Blood & Glory 2 : Le) 绳索救援 ( Rope Rescue )
      子弹时间(Bullet Time) 松饼骑士(Muffin Knight) 狂奔弗雷德 (Running Fred) 荒谬剧场 (Theatre of the Absurd)
      纸片怪兽 Create! Pottery 愚蠢的僵尸 (Stupid Zombies) Bag It！ 攻城大战 (Aiegecraft) 飙车战警 (Smash Cops)
      AVP: Evolution 崩坏学园（The end of school) 🐴天天飞车🐴 Alien Hive Darklings 🐴全民炫舞🐴 口袋四驱车 心灵颤音
      OXkong 纪念碑谷（Monument Valley） Duty Driver Bus（FULL）（公交司机） Duty Driver Taxi（FULL）（出租车司机）
      Duty Driver Firetruck（FULL）（救火车司机）Fried Aircraft（炸飞机）

　　Unity3D对于游戏开发者们来说是一个真正可以负担的起的引擎，具有其他引擎难以匹敌的用户量。
      更为重要的是，你只需要付费一次，而且，不管你的游戏如何成功，都不用担心Unity会分走你的收入。
      这对于很多开发商来说当然是非常具有吸引力对，尤其是初创公司和新入行的开发者们
　　优点：业内最具竞争力的授权条款；易于使用而且兼容所有游戏平台；
        开发者社区支持强大；学习门槛非常低；开发商使用率最高。
　　缺点：工具数量有限，所以开发商必须给自己创作工具；做复杂和多样化的效果比较耗时。

　　虚幻引擎
    《战争机器》《帕拉贝伦》《彩虹六号：维加斯》《生化奇兵》《枪神》《虚幻竞技场3》《荣誉勋章：空降神兵》
    《彩虹六号：维加斯2》《前线：战火之源》《恐龙猎人》《转折点:自由的陨落》《格林童话惊魂记》《战火兄弟连：地狱公路》
    《潘多拉的魔盒》《镜之边缘》《质量效应》《阿尔戈英雄的崛起》《战地之王》《战争机器2》《美国陆军3》《致命车手》
    《终结战争》《最后的神迹》《边境之地》《诅咒》《异形:殖民军》🐴《X战警前传：金刚狼》🐴《蝙蝠侠：阿卡姆疯人院》🐴
    《一舞成名》《神兵传奇》《Hessian》🐴《流星蝴蝶剑OL》🐴《聊斋OL》 《BERKANIX》《犯罪艺术》《全球计划》
    《无双OL》🐴《质量效应2》🐴《中华英雄》《细胞分裂5》 《奇点》《爱丽丝疯狂回归》《绝对火力》《全球使命》
    《荣誉勋章》《风暴战区》《Huxley》《阿尔法协议》《奇异人生》《特殊行动：一线生机》


　　数年以来，虚幻引擎一直是做高端EA游戏最受欢迎的引擎。《战争机器》、《蝙蝠侠：阿卡汉姆疯人院》
        (Batman: Arkham Asylum)、《质量效应》以及很多大作都是出自该引擎之手
　　优点：开发商使用率较高，开发商社区支持支持强大，有视频教程和大量资源。
        最佳的引擎支持并且随时更新其他引擎平台的功能，每次更新都会增加新工具，而且管理相对容易，
        有些工具甚至小学生都会使用。兼容大多数平台，比如iOS、Android、Linux、Mac、Windows和大多数游戏主机。
　　缺点：授权条款只适合大作，商业授权价格为99美元，在游戏收入超过5万美元之后，必须支付25%的分成。
        也有一些开发者抱怨有些工具不好用，学习门槛较高。

　　CryEngine 3

　　该游戏引擎以优质的画面输出获得了大量开发者认可，如果你要做视觉出色的游戏，这款引擎绝对是最理想的选择。
　　优点：CryEngine 3可以让你的游戏更美丽，Flowgraph工具的美术编程能力非常强悍。该引擎具备最强悍的音频工具，
      所以音频策划和程序猿们非常喜欢。该游戏引擎还提供目前最为简单易用的AI代码技术，对于初入行的开发者，
      该引擎的UI触手可及。
　　缺点：免费榜缺乏客户支持；推出时间相对较晚，开发者社区还不够强大；学习门槛对于初入行这比较高。

　　HeroEngine
　　该引擎在MMO和在线游戏领域获得了非常高的人气，代表作《星球大战：旧共和国》。
        对于新入行的开发者以及初创公司来说，授权费用较高，不过，如果你有一个非常具备潜力的项目，
        该引擎还是非常值得考虑的。以下是使用该引擎之前需要考虑的优点与缺点：
　　优点：提供多个开放世界地图，而且可以实现无缝转换；提供相对完善的AI；地图工具简单易用，并且集成了多个工具；
        脚本强大，足够帮助开发者研发复杂的项目、获得需要的资源；可以通过HeroCloud支持客户服务器。
　　缺点：脚本引擎强大但不够直观；HeroEngine和HeroCloud对于初创公司来说成本较高；新开发者学习门槛较高。

　　Rage Engine
　　该引擎的用途非常多，比较知名的游戏包括GTA Ⅲ、GTA：Vice City、GTA：San Andreas和很多知名大作。
　　优点：兼容与处理较大世界观和天气特效方面非常出色；复杂的AI设计方面领先其他引擎；非常适合多种玩法的游戏；
        网络编程速度非常快；非常具有吸引力的画质水平。
　　缺点：和其他顶级引擎相比界面比较差；对于键盘和鼠标控制优化做的不足。

　　Project Anarchy
　　该引擎是一套完整的端到端游戏引擎和尖端移动设备工具组，受到很多游戏开发者赞誉
　　优点：提供免费的手游研发工具(主要平台，比如iOS、Android和Tizen)；拥有非常强悍的程序调试工具；
         非常活跃的开发者社区与论坛；编辑器非常强大；音频输出能力非常好；优秀的Havok AI；
         vForge为开发者提供大量的定制化选择。
　　缺点：不支持Mac和Linux开发环境；没有新手教学；对于初创公司来说成本较高。

　　GameSalad
　　这款引擎据说是不用写代码就能做游戏。这并不是个噱头，该引擎的确支持这样的功能
　　优点：如果你想独立开发一款iPhone游戏，该引擎非常适合你；对于快速实现游戏想法来说，
        GameSalad是个不错的引擎；兼容流行的手游研发平台，比如Cocona和Moai。
　　缺点：研发工具限制性比较强；缺乏大量的iOS功能；不兼容所有的平台。

　　GameMaker：Studio
　　作为开发者，如果你想要一款简单而又快速直接的游戏引擎开始项目，那么GameMaker：Studio绝对是理想之选；
      尽管授权费有些贵，但能够获得的功能还是物有所值的
　　优点：对于所有开发者来说都非常简单和直接；加入了编程语言(GML)；不需要处理内存管理或者多线程等方面的任务；
          独立于任何平台。
　　缺点：在内存问题方面的程序调试比较麻烦；授权费相对昂贵。

　　App Game Kit
　　该引擎是真正的跨平台研发工具，非常易用、简单，而且比较灵活。以下是该引擎的优缺点：
　　优点：可以为多平台写代码，包括Android、iOS、Windows、Mac和Linux；集成Design Environment，
        可以在任何设备调试；加入了IAP、AdMob以及Push等工具；AGK脚本非常强大。
　　缺点：使用者较少，所以学习起来相对较慢；BUG比较多；传感器或者GPS支持比较差。

　　Cocos2D
　　很多策划认为Cocos2D对于新入行的开发者来说不仅具备大量功能，而且非常容易上手。虽然该引擎比较复杂，
      但值得一提的是其功能和灵活性
　　优点：强大而且灵活；理论上来讲，你可以为自己的游戏加入所有的iOS功能；提供成熟的框架和多种工具；
        开源、免费，社区支持强大。
　　缺点：和同类引擎相比比较复杂；学习门槛相对较高；特别适合Mac或者iOS平台，不过并不是跨平台引擎。
　　如今人们在各种平台都玩游戏，比如主机、移动设备甚至是智能电视，所以，开发商在选择引擎的时候，
    需要找到适合自己技术并且能够满足目标市场要求的引擎，因此合适的引擎对于开发商们来说尤其重要，
    特别是新入行的开发者们。

4. 《围住神经猫》游戏引擎： 白鹭 Egret Engine

  1. 基于TypeScript及JavaScript技术 支持Flash到Egret高效转换 引擎、工具、运行时完整工作流
  2. 近11款免费可视化工具体系 打造游戏开发工作流 兼容Adobe Flash工作流
  3. 跨平台 HTML5,iOS,Android,Windows Phone
  4. 全中文文档 文档与开发者社区齐全
  5. 开源免费，BSD开源协议 任意定制及扩展
  6. 极简安装开发环境 一键安装包

5 相关咨询

  1. 微信正在限制H5游戏传播
   在《围住神经猫》等基于HTML5技术的小游戏在微信朋友圈成功传播后，很多开发者都尝试复制其奇迹，
   并希望通过接入广告获取收入。因此，前端时间不少用户的朋友圈不断被H5游戏刷屏，但最近这个情况有所减少，
   有H5游戏开发者表示，除了游戏开发方面的问题，微信主动限制HTML5游戏在朋友圈中传播也是重要原因。

　　前述开发者透露，如今微信在一款H5游戏达到一定数量IP访问时，就会限制传播，限制方法主要是使分享内容在朋友圈不可见，
   即用户将游戏分享至朋友圈后，只有自己能够看到分享内容。
　　对于具体的访问IP数量，有开发者表示，他们的经验是在最低十几万左右，被限制传播后，他们一般会尝试更换游戏域名等方法，
   与微信打“游击战”。同时，另外的开发者表示，大家都知道微信在限制H5游戏传播，但标准目前很模糊，
   只知道游戏访问量大的时候会被注意到。最早的《神经猫》、《看你有多色》等实现朋友圈“病毒式传播”的H5游戏，
   都实现了超过千万IP的访问，微信主动限制H5游戏传播，等于为H5游戏在微信中设置了远低于从前的天花板，
   很大程度上降低了开发者复制《神经猫》成功的可能性。对于微信限制H5游戏传播的看法，有开发者表示，
   从微信的角度看，他们的想法肯定是维护微信用户体验。从目前情况看，微信H5游戏在朋友圈大量传播，
   确实在一定程度上冲击了微信的用户体验。另据腾讯内部知情人士透露，HTML5游戏在朋友圈内大量传播、
   接入广告混乱等问题都引起了微信关注，微信目前虽然不会封杀HTML5游戏，但一定会进行规范。

  2. 微信正在限制H5游戏传播，X5引擎或为敲门砖。

    X5内核是腾讯基于优秀开源Webkit  深度优化的浏览器渲染引擎，搭载在最新一代的手机QQ浏览器上，更快，更便捷。
    2014年9月23日，腾讯正式宣布开放业内首个浏览服务开放平台，向APP开发者共享腾讯X5浏览服务，
    推动移动互联网的“浏览蝶变”。微信、手机QQ、新浪新闻、凤凰新闻、搜狐视频、京东等各类共30多款知名APP成为首批受益者。
    腾讯X5由X5内核及其相关云服务构成，基于WebKit深度优化和合理扩展的X5内核，全面整合腾讯公司在云安全、
    云加速和大数据分析应用等相关领域的研发和运营能力，成就新一代智能浏览内核

  3. 腾讯X5联手白鹭EgretRuntime 共推HTML5游戏
    2014.9.23

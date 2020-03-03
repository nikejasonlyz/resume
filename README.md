<!DOCTYPE html>
<html lang="zh-cn">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no"
    />
    <meta name="apple-mobile-web-app-status-bar-style" content="black" />
    <meta name="format-detection" content="email=no" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="format-detection" content="telephone=no" />
    <meta name="renderer" content="webkit">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="apple-mobile-web-app-title" content="Amaze UI" />
    <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate" />
    <meta http-equiv="Pragma" content="no-cache" />
    <meta http-equiv="Expires" content="0" />
    <title>[Resume]about him/CDUT</title>
    <link rel="shortcut icon" href="assets/images/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="assets/css/typo.css">
    <link rel="stylesheet" href="assets/css/font-awesome.min.css">
    <link rel="stylesheet" href="assets/css/index.css">
    <script>
        function loading() {
            document.getElementsByClassName('avatar')[0].style.display = 'block';
            document.getElementsByClassName('loading')[0].style.display = 'none';
        }
    </script>
</head>

<body>

    <header class="header"></header>

    <article class="container">
        <section class="side" id="side">

            <!-- 左栏固定开关，记得及时删除这段代码 Start-->
            <label class="switch" style="display: none;" onchange="switchFixed()">
                <script type="text/javaScript">
                    function switchFixed(){
                        var value = document.getElementById('side').style.position === 'fixed' ? 'absolute' : 'fixed';
                        document.getElementById('side').style.position = value;
                    }
                </script>
                <input id="cb" type="checkbox">
                <span class="slider round"></span>
            </label>
            <style>
                @media (min-width: 414px){
                    .switch{position:relative;display:inline-block!important;width:60px;height:34px;}
                    .switch input{display:none;}
                    .slider{position:absolute;cursor:pointer;top:0;left:0;right:0;bottom:0;background-color:#ccc;-webkit-transition:.4s;transition:.4s;}
                    .slider:before{position:absolute;content:"";height:26px;width:26px;left:4px;bottom:4px;background-color:white;-webkit-transition:.4s;transition:.4s;}
                    input:checked + .slider{background-color:#1abc9c;}
                    input:focus + .slider{box-shadow:0 0 1px #1abc9c;}
                    input:checked + .slider:before{-webkit-transform:translateX(26px);-ms-transform:translateX(26px);transform:translateX(26px);}.slider.round{border-radius:34px;}
                    .slider.round:before{border-radius:50%;}
                }
            </style>
            <!-- 左侧固定开关，记得及时删除这段代码 End-->

            <!-- 个人肖像 -->
            <section class="me">
                <section class="portrait">
                    <div class="loading">
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                    <!-- 头像照片 -->
                    <img class="avatar" src="assets/images/avatar.png" onload="loading()">
                </section>

                <h1 class="name">木木君</h1>
                <h4 class="info-job">学生 / CDUT</h4>

            </section>

            <!-- 基本信息 -->
            <section class="profile info-unit">
                <h2>
                    <i class="fa fa-user" aria-hidden="true"></i>基本信息</h2>
                <hr/>
                <ul>
                    <li>
                        <label>个人信息</label>
                        <span>袁林 / 男 / 19岁</span>
                    </li>
                    <li>
                        <label>英语水平</label>
                        <span>有待考核</span>
                    </li>
                    <li>
                        <label>计算机水平</label>
                        <span>有待考核</span>
                    </li>
                </ul>
            </section>

            <!-- 联系方式 -->
            <section class="contact info-unit">
                <h2>
                    <i class="fa fa-phone" aria-hidden="true"></i>联系方式</h2>
                <hr/>
                <ul>
                    <li>
                        <label>手机</label>
                        <a href="tel:18009073880" target="_blank">180-0907-3880</a>
                    </li>
                    <li>
                        <label>邮箱</label>
                        <a href="mailto:nikejasonlyz@outlook.com" target="_blank">nikejasonlyz@outlook.com</a>
                    </li>
                    <li>
                        <label>Blog</label>
                        <a href="https://nikejasonlyz.github.io" target="_blank">blog/</a>
                    </li>
                    </li>
                    <li>
                        <label>Github</label>
                        <a href="https://github.com/nikejasonlyz" target="_blank">github.com/nikejasonlyz</a>
                    </li>
                </ul>
            </section>

            <!-- 技能点 -->
            <section class="skill info-unit">
                <h2>
                    <i class="fa fa-code" aria-hidden="true"></i>技能点</h2>
                <hr/>
                <ul>
                    <li>
                        <label>学</label>
                        <progress value="90" max="100"></progress>
                    </li>
                    <li>
                        <label>吃</label>
                        <progress value="85" max="100"></progress>
                    </li>
                    <li>
                        <label>喝</label>
                        <progress value="85" max="100"></progress>
                    </li>
                    <li>
                        <label>玩</label>
                        <progress value="85" max="100"></progress>
                    </li>
                    <li>
                        <label>睡</label>
                        <progress value="70" max="100"></progress>
                    </li>
                    <li>
                        <label>呆</label>
                        <progress value="70" max="100"></progress>
                    </li>
                </ul>
            </section>

            <section class="qrcode info-unit">
                <h2><i class="fa fa-qrcode" aria-hidden="true"></i>二维码</h2>
                <hr/>
                <img src="assets/images/mmqrcode.png" style="width: 100%;" alt="">
            </section>

            <!-- 技术栈 -->
            <!-- <div class="stack info-unit">
                    <h2><i class="fa fa-code" aria-hidden="true"></i>其他</h2>
                    <hr/>
                    <ul>
                        <li>
                            <label>前端</label>
                            <span>React、jQuery、微信小程序、Bootstrap、SASS、LESS</span>
                        </li>
                        <li>
                            <label>后端</label>
                            <span>Node.js、MySQL、MongoDB、WordPress、ThinkPHP</span>
                        </li>
                        <li>
                            <label>其他</label>
                            <span>Git、SVN、Markdown</span>
                        </li>
                    </ul>
                </div> -->
        </section>

        <section class="main">

            <section class="intro">
                <h2>
                    <i class="fa fa-terminal" aria-hidden="true"></i>注意</h2>
                <hr>
                <ul>
                    <li>
                        <h3>
                            <span>注意注意注意有用的再说三遍</span>
                            <time>2019.1.23</time>
                        </h3>
                        <p>此简历模板源自[拾迹](https://github.com/uhr)
                            <mark>干年后简历模板应该是会参考于此的，有需求的朋友可以去拾迹的仓库了解(目前我就用来记录一些小事件叭)</mark></p>
                    </li>
                </ur>
            </section>
            <!-- 教育经历 -->
            <section class="edu info-unit">
                <h2>
                    <i class="fa fa-graduation-cap" aria-hidden="true"></i>教育经历</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>XXXX大学 - XXX专业（硕士）</span>
                            <time>202X.9-202X.7（这是未来）</time>
                        </h3>
                        <p>专业排名
                            <mark>X/XX</mark>，（这里填）期间发表国际会议英文摘要X篇，国内核心期刊文章X篇（其中第一作者X篇），获XXX，XXX次，XXX次。(此处根据自身情况填写，可以突出自己的亮点，或者跟求职目标相关的内容)</p>
                    </li>
                    <li>
                        <h3>
                            <span>成都理工大学 - 电子信息类专业（本科）</span>
                            <time>2018.9-2022.7</time>
                        </h3>
                        <p>专业排名
                            <mark>X/XX</mark>，（迟早会有我的）期间发表国内核心期刊文章X篇，三等奖学金X次。</p>
                    </li>
                </ul>
            </section>

            <!-- 工作经历 -->
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-shopping-bag" aria-hidden="true"></i>课余经历</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>[经历1]朋友XX公司－服务器维护</span>
                            <time>2016.6 至 2018.4</time>
                        </h3>
                        <ul class="info-content">
                            <li>暂无特点
                                <mark>嘘</mark>不可能的
                                <mark>你想不想知道</mark>。</li>
                            <li>我都
                                <mark>不会</mark>,</li>
                            <li>告诉你！
                                <mark>尬笑</mark>。</li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>[经历2]软件开发项目python（暂定）</span>
                            <time>2018.10-20XX.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>仍处于审核期中，
                                <mark>Python自学中</mark>每日还是少不了敲代码的，大学以来第一个寒假没想到会以做实验报告为起点。后续会在博客登载。
                                <a href="https://nikejasonlyz.github.io/" target="_blank">
                                    <i class="fa fa-link" aria-hidden="true"></i>博客文章</a>。</li>
                            <li>加油啊，虽然常常连续熬夜到五点
                                <mark>未来的我会感谢现在努力的自己</mark>虽然也会抱怨当初磨耗太多青春吧</li>
                            <li>但无论如何</li>
                            <li>DoBelieve
                                <mark>未来可期</mark>（继续敲着这一页）
                                <a href="#" target="_blank">
                                    <i class="fa fa-link" aria-hidden="true"></i>博客文章</a>。</li>
                        </ul>
                    </li>
                </ul>
            </section>

            <!-- 项目经验 -->
            <section class="project info-unit">
                <h2>
                    <i class="fa fa-terminal" aria-hidden="true"></i>个人项目（暂时该叫小破烂叭）</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>[项目1]Android Tool-like App</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>2015.3-2017.9</time>
                        </h3>
                        <ul class="info-content">
                            <li>不讲了不讲了 免得装逼嫌疑</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]整合了浏览器、科学计算器、二维码转换、配色卡，加入基于css编译的夜间模式调节、视频全屏播放、强制抓取页面资源下载链（该借鉴于XDM for Ubuntu、IDM in windows及其它嗅探api）
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [感受]可海星？
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]完成从
                                <mark>“需求分析-详细设计-编码-测试-上线”</mark>等工作
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]隔壁小孩都馋哭了</li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>[项目2]哎算了 真不讲了</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>2016.6-2018.2</time>
                        </h3>
                        <ul class="info-content">
                            <li>不讲</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]不告诉你
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]与 1 个女儿
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]技拙不讲了（其实还真没什么讲的👀）
                                <mark>emm</mark> 就是这样
                                <mark>😂😂😂</mark> 没有什么特别的
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]真的没有😂😂😂
                            </li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>[项目3]即准备做的软件开发与优化</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>2018.10-201X.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：Python+C#+MySQL</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]看标题就知道了细节不告诉你
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]有谁？
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]暂无
                                <mark>😂</mark> 或许
                                <mark>以后多着</mark> 😂
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]有待未来
                            </li>
                        </ul>
                    </li>
                </ul>
            </section>

            <!-- 自我评价 -->
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-pencil" aria-hidden="true"></i>自我评价/期望</h2>
                <hr/>
                <p>[此处如果有一些能够量化的、且比较个性的指标会有加分，比如喜爱跑步坚持夜跑200小时或者200km等]
                    <span class="mark-txt">“脚踏实地，行称致远”</span>是鄙人的“八字箴言”</p>
            </section>
        </section>
    </article>



    <footer class="footer">
        <p>© 2019 木木君.文档最后更新时间为
            <time>2019年01月23日</time>.</p>
    </footer>

    <!-- 侧栏 -->
    <aside>
        <ul>
            <li>
                <a href="https://github.com/nikejasonlyz/resume" target="_blank">源代码</a>
            </li>
            <li>
                <a href="http://nikejasonlyz.github.io/" target="_blank">Blog</a>
            </li>
        </ul>
    </aside>

    <script src="./assets/js/index.js"></script>
</body>

</html>

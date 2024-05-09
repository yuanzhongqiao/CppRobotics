<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cpp机器人公司</font></font></h1><a id="user-content-cpprobotics" class="anchor" aria-label="永久链接：CppRobotics" href="#cpprobotics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://github.com/AtsushiSakai/PythonRobotics"><font style="vertical-align: inherit;">这是PythonRobotics</font></a><font style="vertical-align: inherit;">的cpp实现</font></font><a href="https://github.com/AtsushiSakai/PythonRobotics"><font style="vertical-align: inherit;"></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h2><a id="user-content-requirment" class="anchor" aria-label="永久链接： 要求" href="#requirment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cmake</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放式CV 3.3</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本征3</font></font></li>
<li><a href="https://www.coin-or.org/CppAD/Doc/install.htm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CppAD</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> / </font></font><a href="https://www.coin-or.org/Ipopt/documentation/node14.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IPOPT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于MPC凸优化</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font><a href="https://github.com/udacity/CarND-MPC-Quizzes/blob/master/install_Ipopt_CppAD.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装提示</font></font></a></li>
<li><del><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">活性氧</font></font></del><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><em><del><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使仓库变得轻量级:)</font></font></del><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。然而，我们可能仍然需要它来进行 3D 可视化。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建造</font></font></h2><a id="user-content-build" class="anchor" aria-label="永久链接：构建" href="#build"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code> $ mkdir build
 $ cd build
 $ cmake ../
 $ make -j 8
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" $ mkdir build
 $ cd build
 $ cmake ../
 $ make -j 8" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><em><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到build/bin</font></font></strong></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的所有可执行文件</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h1><a id="user-content-table-of-contents" class="anchor" aria-label="固定链接：目录" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#localization"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本土化</font></font></a>
<ul dir="auto">
<li><a href="#extended-kalman-filter-localization"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扩展卡尔马过滤器</font></font></a></li>
<li><a href="#particle-filter-localization"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">颗粒过滤器</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直方图过滤器</font></font></li>
</ul>
</li>
<li><a href="#mapping"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测绘</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高斯网格图</font></font></li>
</ul>
</li>
<li><a href="#SLAM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SLAM</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速SLAM 1.0</font></font></li>
</ul>
</li>
<li><a href="#path-planning"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路径规划</font></font></a>
<ul dir="auto">
<li><a href="#dijkstra"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迪克斯特拉</font></font></a></li>
<li><a href="#a-star"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个明星</font></font></a></li>
<li><a href="#rrt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">恢复时间</font></font></a></li>
<li><a href="#dynamic-window-approach"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态窗口方法</font></font></a></li>
<li><a href="#model-predictive-trajectory-generator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型预测轨迹生成器</font></font></a></li>
<li><a href="#cubic-spline-planner"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">三次样条规划器</font></font></a></li>
<li><a href="#state-lattice-planner"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状态格规划器</font></font></a></li>
<li><a href="#frenet-frame-trajectory"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Frenet框架轨迹</font></font></a></li>
</ul>
</li>
<li><a href="#path-tracking-control"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路径跟踪控制</font></font></a>
<ul dir="auto">
<li><a href="#lqr-steering-control"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LQR 转向控制</font></font></a></li>
<li><a href="#lqr-speed-and-steering-control"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LQR 速度和转向控制</font></font></a></li>
<li><a href="#mpc-speed-and-steering-control"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型预测速度和转向控制</font></font></a></li>
</ul>
</li>
<li><a href="#aerial-navigation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">空中导航</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无人机 3D 轨迹跟踪</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">火箭动力着陆</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本土化</font></font></h1><a id="user-content-localization" class="anchor" aria-label="永久链接：本地化" href="#localization"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扩展卡尔曼滤波器定位</font></font></h2><a id="user-content-extended-kalman-filter-localization" class="anchor" aria-label="永久链接：扩展卡尔曼滤波器定位" href="#extended-kalman-filter-localization"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">绿线：真实轨迹</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑线：航位推算</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红点：观测值（例如 GPS）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝线：估计位置</font></font></li>
</ul>

<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/a1a26cafc0ded3fdc1796695479f80f6f45077ced20783cbb8c38912c2973c92/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f656b662e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/a1a26cafc0ded3fdc1796695479f80f6f45077ced20783cbb8c38912c2973c92/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f656b662e676966" alt="埃克夫" data-canonical-src="https://ram-lab.com/file/tailei/gif/ekf.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/a1a26cafc0ded3fdc1796695479f80f6f45077ced20783cbb8c38912c2973c92/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f656b662e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="埃克夫" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/a1a26cafc0ded3fdc1796695479f80f6f45077ced20783cbb8c38912c2973c92/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f656b662e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/a1a26cafc0ded3fdc1796695479f80f6f45077ced20783cbb8c38912c2973c92/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f656b662e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><a href="http://www.probabilistic-robotics.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率机器人学</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">粒子过滤器定位</font></font></h2><a id="user-content-particle-filter-localization" class="anchor" aria-label="永久链接：粒子过滤器本地化" href="#particle-filter-localization"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">绿线：真实轨迹</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑线：航位推算</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红点：地标</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝线：估计位置</font></font></li>
</ul>

<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/82ebf10fa9f0d8150010304593b9871b58364f4c599dbff7c578ac3e97c0615c/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f70662e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/82ebf10fa9f0d8150010304593b9871b58364f4c599dbff7c578ac3e97c0615c/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f70662e676966" alt="普夫" data-canonical-src="https://ram-lab.com/file/tailei/gif/pf.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/82ebf10fa9f0d8150010304593b9871b58364f4c599dbff7c578ac3e97c0615c/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f70662e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="普夫" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/82ebf10fa9f0d8150010304593b9871b58364f4c599dbff7c578ac3e97c0615c/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f70662e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/82ebf10fa9f0d8150010304593b9871b58364f4c599dbff7c578ac3e97c0615c/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f70662e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><a href="http://www.probabilistic-robotics.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率机器人学</font></font></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路径规划</font></font></h1><a id="user-content-path-planning" class="anchor" aria-label="永久链接：路径规划" href="#path-planning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迪克斯特拉</font></font></h2><a id="user-content-dijkstra" class="anchor" aria-label="永久链接：迪杰斯特拉" href="#dijkstra"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝点：起点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红点：目标点</font></font></li>
</ul>
<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/eded2fb749a4de2678e6f4952d3101c0af029bf1d242d36b73651fc4ab50350e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f64696a6b737472612e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/eded2fb749a4de2678e6f4952d3101c0af029bf1d242d36b73651fc4ab50350e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f64696a6b737472612e676966" alt="迪克斯特拉" data-canonical-src="https://ram-lab.com/file/tailei/gif/dijkstra.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/eded2fb749a4de2678e6f4952d3101c0af029bf1d242d36b73651fc4ab50350e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f64696a6b737472612e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="迪克斯特拉" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/eded2fb749a4de2678e6f4952d3101c0af029bf1d242d36b73651fc4ab50350e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f64696a6b737472612e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/eded2fb749a4de2678e6f4952d3101c0af029bf1d242d36b73651fc4ab50350e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f64696a6b737472612e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个明星</font></font></h2><a id="user-content-a-star" class="anchor" aria-label="永久链接：一颗星" href="#a-star"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝点：起点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红点：目标点</font></font></li>
</ul>
<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/6fd56172e32fa374f01ef3fefff6b72b58f20a351755602e79695ef0130f0cab/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f615f737461722e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/6fd56172e32fa374f01ef3fefff6b72b58f20a351755602e79695ef0130f0cab/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f615f737461722e676966" alt="一个明星" data-canonical-src="https://ram-lab.com/file/tailei/gif/a_star.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/6fd56172e32fa374f01ef3fefff6b72b58f20a351755602e79695ef0130f0cab/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f615f737461722e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="一个明星" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/6fd56172e32fa374f01ef3fefff6b72b58f20a351755602e79695ef0130f0cab/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f615f737461722e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/6fd56172e32fa374f01ef3fefff6b72b58f20a351755602e79695ef0130f0cab/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f615f737461722e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">恢复时间</font></font></h2><a id="user-content-rrt" class="anchor" aria-label="永久链接：RRT" href="#rrt"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红色圆圈：起点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝色圆圈：目标点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑圈：障碍物</font></font></li>
</ul>
<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/7d880bd76d9fd028106f918667ff8c556c1e1dff4d104c09d4c6b291488da470/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f7272742e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/7d880bd76d9fd028106f918667ff8c556c1e1dff4d104c09d4c6b291488da470/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f7272742e676966" alt="反应时间" data-canonical-src="https://ram-lab.com/file/tailei/gif/rrt.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/7d880bd76d9fd028106f918667ff8c556c1e1dff4d104c09d4c6b291488da470/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f7272742e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="反应时间" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/7d880bd76d9fd028106f918667ff8c556c1e1dff4d104c09d4c6b291488da470/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f7272742e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/7d880bd76d9fd028106f918667ff8c556c1e1dff4d104c09d4c6b291488da470/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f7272742e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态窗口方法</font></font></h2><a id="user-content-dynamic-window-approach" class="anchor" aria-label="永久链接：动态窗口方法" href="#dynamic-window-approach"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝色圆圈：目标点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红圈：机器人</font></font></li>
</ul>

<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/cb5dd4bce1afcaf255a2477c4e632b35fafa1108ba399f491c788a3b9ff9467f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6477612e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/cb5dd4bce1afcaf255a2477c4e632b35fafa1108ba399f491c788a3b9ff9467f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6477612e676966" alt="德瓦" data-canonical-src="https://ram-lab.com/file/tailei/gif/dwa.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/cb5dd4bce1afcaf255a2477c4e632b35fafa1108ba399f491c788a3b9ff9467f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6477612e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="德瓦" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/cb5dd4bce1afcaf255a2477c4e632b35fafa1108ba399f491c788a3b9ff9467f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6477612e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/cb5dd4bce1afcaf255a2477c4e632b35fafa1108ba399f491c788a3b9ff9467f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6477612e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><a href="https://ieeexplore.ieee.org/document/580977" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态窗口避免碰撞的方法</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型预测轨迹生成器</font></font></h2><a id="user-content-model-predictive-trajectory-generator" class="anchor" aria-label="永久链接：模型预测轨迹生成器" href="#model-predictive-trajectory-generator"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这部分基于自行车运动模型。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝色圆圈：目标点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红圈：初始点</font></font></li>
</ul>

<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/631dc6a3eff1b964ab1373dffbf0f9fc02acae249fc681bece77039d7836f56f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d7074672e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/631dc6a3eff1b964ab1373dffbf0f9fc02acae249fc681bece77039d7836f56f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d7074672e676966" alt="mptg" data-canonical-src="https://ram-lab.com/file/tailei/gif/mptg.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/631dc6a3eff1b964ab1373dffbf0f9fc02acae249fc681bece77039d7836f56f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d7074672e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="mptg" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/631dc6a3eff1b964ab1373dffbf0f9fc02acae249fc681bece77039d7836f56f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d7074672e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/631dc6a3eff1b964ab1373dffbf0f9fc02acae249fc681bece77039d7836f56f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d7074672e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">三次样条规划器</font></font></h2><a id="user-content-cubic-spline-planner" class="anchor" aria-label="永久链接：三次样条规划器" href="#cubic-spline-planner"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/ad59e30ea8ab29f02ab02c4d828c0653c87646d25ad80f45b5313306ee65356f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6373702e706e67"><img src="https://camo.githubusercontent.com/ad59e30ea8ab29f02ab02c4d828c0653c87646d25ad80f45b5313306ee65356f/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6373702e706e67" alt="芯片封装" width="400" data-canonical-src="https://ram-lab.com/file/tailei/gif/csp.png" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状态格规划器</font></font></h2><a id="user-content-state-lattice-planner" class="anchor" aria-label="永久链接：状态格规划器" href="#state-lattice-planner"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝色圆圈：目标点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红圈：初始点</font></font></li>
</ul>

<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/0a842d0de01c1a368596e3025150aab792917ab61b6d224cfd4aab506b49a122/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f736c702e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/0a842d0de01c1a368596e3025150aab792917ab61b6d224cfd4aab506b49a122/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f736c702e676966" alt="斯拉普" data-canonical-src="https://ram-lab.com/file/tailei/gif/slp.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/0a842d0de01c1a368596e3025150aab792917ab61b6d224cfd4aab506b49a122/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f736c702e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="斯拉普" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/0a842d0de01c1a368596e3025150aab792917ab61b6d224cfd4aab506b49a122/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f736c702e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/0a842d0de01c1a368596e3025150aab792917ab61b6d224cfd4aab506b49a122/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f736c702e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><a href="https://www.ri.cmu.edu/pub_files/pub4/howard_thomas_2008_1/howard_thomas_2008_1.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">复杂环境下高性能移动机器人导航可行运动的状态空间采样</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Frenet框架轨迹</font></font></h2><a id="user-content-frenet-frame-trajectory" class="anchor" aria-label="永久链接： Frenet 框架轨迹" href="#frenet-frame-trajectory"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑线：规划的样条路径</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红色圆圈：障碍物</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝色圆圈：计划轨迹</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">绿色圆圈：机器人实时位置</font></font></li>
</ul>
<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/293fb5dcd5b4ce983d502cfe9a7a65ea74fc23d2515397a1d670a0f92611ce05/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6672656e65742e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/293fb5dcd5b4ce983d502cfe9a7a65ea74fc23d2515397a1d670a0f92611ce05/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6672656e65742e676966" alt="弗雷内特" data-canonical-src="https://ram-lab.com/file/tailei/gif/frenet.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/293fb5dcd5b4ce983d502cfe9a7a65ea74fc23d2515397a1d670a0f92611ce05/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6672656e65742e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="弗雷内特" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/293fb5dcd5b4ce983d502cfe9a7a65ea74fc23d2515397a1d670a0f92611ce05/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6672656e65742e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/293fb5dcd5b4ce983d502cfe9a7a65ea74fc23d2515397a1d670a0f92611ce05/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6672656e65742e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><a href="https://www.researchgate.net/publication/224156269_Optimal_Trajectory_Generation_for_Dynamic_Street_Scenarios_in_a_Frenet_Frame" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Frenet 框架中动态街道场景的最优轨迹生成</font></font></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路径跟踪控制</font></font></h1><a id="user-content-path-tracking-control" class="anchor" aria-label="永久链接：路径跟踪控制" href="#path-tracking-control"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LQR 转向控制</font></font></h2><a id="user-content-lqr-steering-control" class="anchor" aria-label="永久链接：LQR 转向控制" href="#lqr-steering-control"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑线：规划的样条路径</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红圈：lqr控制下的位置</font></font></li>
</ul>
<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/311e769a7283d1355461536fa2bd23e0088f1d83df73d13e7733096e207fe737/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f7374656572696e672e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/311e769a7283d1355461536fa2bd23e0088f1d83df73d13e7733096e207fe737/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f7374656572696e672e676966" alt="lqr_转向" data-canonical-src="https://ram-lab.com/file/tailei/gif/lqr_steering.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/311e769a7283d1355461536fa2bd23e0088f1d83df73d13e7733096e207fe737/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f7374656572696e672e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="lqr_转向" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/311e769a7283d1355461536fa2bd23e0088f1d83df73d13e7733096e207fe737/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f7374656572696e672e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/311e769a7283d1355461536fa2bd23e0088f1d83df73d13e7733096e207fe737/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f7374656572696e672e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LQR 速度和转向控制</font></font></h2><a id="user-content-lqr-speed-and-steering-control" class="anchor" aria-label="永久链接：LQR 速度和转向控制" href="#lqr-speed-and-steering-control"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑线：规划的样条路径</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红圈：lqr控制下的位置</font></font></li>
</ul>
<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/69f5d1726fab1803b07e0d42b81821d939db47df1451ec1112a09df76fc6a66e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f66756c6c2e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/69f5d1726fab1803b07e0d42b81821d939db47df1451ec1112a09df76fc6a66e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f66756c6c2e676966" alt="lqr_full" data-canonical-src="https://ram-lab.com/file/tailei/gif/lqr_full.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/69f5d1726fab1803b07e0d42b81821d939db47df1451ec1112a09df76fc6a66e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f66756c6c2e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="lqr_full" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/69f5d1726fab1803b07e0d42b81821d939db47df1451ec1112a09df76fc6a66e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f66756c6c2e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/69f5d1726fab1803b07e0d42b81821d939db47df1451ec1112a09df76fc6a66e/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6c71725f66756c6c2e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MPC 速度和转向控制</font></font></h2><a id="user-content-mpc-speed-and-steering-control" class="anchor" aria-label="永久链接：MPC 速度和转向控制" href="#mpc-speed-and-steering-control"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑线：规划的样条路径</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝线：经过的路径</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黄色十字：MPC的参考轨迹</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
（编译这部分需要取消CMakeLists.txt中相关行的注释并安装</font></font><a href="https://www.coin-or.org/CppAD/Doc/install.htm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CppAD</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://coin-or.github.io/Ipopt/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IPOPT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。）</font></font></li>
</ul>
<p dir="auto"><animated-image data-catalyst="" style="width: 400px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/74f1b0237d85665dd212c42291db38db5165640cd6cd5aae22c7747ef071b796/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d70632e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/74f1b0237d85665dd212c42291db38db5165640cd6cd5aae22c7747ef071b796/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d70632e676966" alt="多普勒" data-canonical-src="https://ram-lab.com/file/tailei/gif/mpc.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/74f1b0237d85665dd212c42291db38db5165640cd6cd5aae22c7747ef071b796/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d70632e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="多普勒" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/74f1b0237d85665dd212c42291db38db5165640cd6cd5aae22c7747ef071b796/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d70632e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/74f1b0237d85665dd212c42291db38db5165640cd6cd5aae22c7747ef071b796/68747470733a2f2f72616d2d6c61622e636f6d2f66696c652f7461696c65692f6769662f6d70632e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
</article></div>

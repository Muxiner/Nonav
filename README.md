# 简易网址导航

修改自 [webstack.cc](https://github.com/WebStackPage/WebStackPage.github.io) —— 静态响应式网址导航网站。

### HTML 模板

**左侧导航栏（使用原项目代码）**：

```HTML
<ul id="main-menu" class="main-menu">
    <li>
        <a href="#常用推荐" class="smooth">
            <i class="linecons-star"></i>
            <span class="title">常用推荐</span>
        </a>
    </li>
    <li>
        <a>
            <i class="linecons-lightbulb"></i>
            <span class="title">灵感采集</span>
        </a>
        <ul>
            <li>
                <a href="#网页灵感" class="smooth">
                    <span class="title">网页灵感</span>
                    <span class="label label-pink pull-right hidden-collapsed">Hot</span>
                </a>
            </li>
        </ul>
    </li>   
</ul>
```

分类标题：

```HTML
<h4 class="text-gray"><i class="linecons-tag" style="margin-right: 7px;" id="常用推荐"></i>常用推荐</h4>
```

列表内容：

```HTML
<div class="row">
    <div class="col-sm-3">
        <div class="xe-widget xe-conversations box2 label-info" onclick="window.open('https://dribbble.com/', '_blank')" data-toggle="tooltip" data-placement="bottom" title="" data-original-title="https://dribbble.com/">
            <div class="xe-comment-entry">
                <a class="xe-user-img">
                    <img data-src="../assets/images/logos/dribbble.png" class="lozad img-circle" width="40">
                </a>
                <div class="xe-comment">
                    <a href="#" class="xe-user-name overflowClip_1">
                        <strong>Dribbble</strong>
                    </a>
                    <p class="overflowClip_2">全球UI设计师作品分享平台。</p>
                </div>
            </div>
        </div>
    </div>
</div>
<br />
    <!-- END 常用推荐 -->
```

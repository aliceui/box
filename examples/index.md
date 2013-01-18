# 演示文档

---

<link type="text/css" rel="stylesheet" media="screen" href="../src/box.css">

## 默认用法

````html
<div class="ui-box">
    <div class="ui-box-head">
        <div class="ui-box-head-border">
            <h3 class="ui-box-head-title">区块标题</h3>
            <span class="ui-box-head-text">其他文字</span>
            <a href="#" class="ui-box-head-more">更多</a>
        </div>
    </div>
    <div class="ui-box-container">
        <div class="ui-box-content">ui-box-content 有默认内边距</div>
    </div>
</div>
````

## 两个 box 相连

````html
<div class="ui-box">
    <div class="ui-box-head">
        <div class="ui-box-head-border">
            <h3 class="ui-box-head-title">区块标题</h3>
            <span class="ui-box-head-text">其他文字</span>
            <a href="#" class="ui-box-head-more">更多</a>
        </div>
    </div>
    <div class="ui-box-container">
        <div class="ui-box-content">ui-box-content 有默认内边距</div>
    </div>
</div>
<div class="ui-box ui-box-follow">
    <div class="ui-box-head">
        <div class="ui-box-head-border">
            <h3 class="ui-box-head-title">连着上面的box</h3>
            <span class="ui-box-head-text">其他文字</span>
            <a href="#" class="ui-box-head-more">更多</a>
        </div>
    </div>
    <div class="ui-box-container">
        <div class="ui-box-content">ui-box-content 有默认内边距</div>
    </div>
</div>
````

## 浅色系

````html
<div class="ui-box ui-box-light">
    <div class="ui-box-head">
        <div class="ui-box-head-border">
            <h3 class="ui-box-head-title">连着上面的box</h3>
            <span class="ui-box-head-text">其他文字</span>
            <a href="#" class="ui-box-head-more">更多</a>
        </div>
    </div>
    <div class="ui-box-container">
        <div class="ui-box-content">ui-box-content 有默认内边距</div>
    </div>
</div>
````

## 内容隐藏

````html
<div class="ui-box ui-box">
    <div class="ui-box-head">
        <div class="ui-box-head-border">
            <h3 class="ui-box-head-title">连着上面的box</h3>
            <span class="ui-box-head-text">其他文字</span>
            <a href="#" class="ui-box-head-more">更多</a>
        </div>
    </div>
    <div class="ui-box-container" style="display: none;">
        <div class="ui-box-content">ui-box-content 有默认内边距</div>
    </div>
</div>
````

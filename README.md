### Button-Hover-Effects
<p>Just Some More  Button Hover Effects</p>
-----------------------------
<style>
    .willGreen{
        color: green;
    }
</style>
------------------------------------
<p>效果查看: <a href="http://wjf444128852.github.io/demo02/MyButtonHover/index.html" target="_blank">http://wjf444128852.github.io/demo02/MyButtonHover/</a></p>
<div>
    <p>原理都是border属性拆开来写</p>
    <pre class="willGreen">
        border:1px solid currentColor;/*currentColor当前文字的颜色*/
        border-style: solid;
        border-width: 0 0 0 0;/*上、右、下、左*/
        border-color: #611c19 transparent transparent transparent;
    </pre>
</div>

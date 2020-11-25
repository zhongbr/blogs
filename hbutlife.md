# 湖工Life

*湖工Life旨在我自己练习编程的过程中，同时为湖工大学子提供一个信息聚合平台。*

下面可以预览哦！原汁原味链接：<a href="https://life.zhongbr.cn">湖工life</a>

<div style="text-align:center;border-radius:20px;overflow:hidden;">
    <iframe id="app" height="560" width="315" src="https://life.zhongbr.cn/index.html"></iframe>
    <script>
        window.onload = function(){
            let scHeight = document.documentElement.clientHeight;
            let scWidth = document.documentElement.clientWidth;
            let iframe = document.getElementById("app");
            if(scHeight>scWidth*16/9){
                iframe.width = scWidth*0.7;
                iframe.height = scWidth*0.7*16/9;
            }
            else{
                iframe.height = scHeight*0.7;
                iframe.width = scHeight*0.7*9/16;
            }
        }
    </script>
</div>

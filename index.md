<!DOCTYPE html><html><head>
    <meta charset="utf-8">
    <title>欢迎来到我的空间</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.staticfile.org/twitter-bootstrap/4.6.0/css/bootstrap.min.css">
    <script src="https://cdn.staticfile.org/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://cdn.staticfile.org/popper.js/1.15.0/umd/popper.min.js"></script>
    <script src="https://cdn.staticfile.org/twitter-bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script src="../static/js/立方体.js"></script>
    <style>
        .carousel-item img {
            width: 100%;
          }
        body {
            width: 95%;
            background: url(../static/images/bg1.png) no-repeat;
            background-size: 100%;
            margin: 4% auto;
        }
        a{
            font-size: 18px;
        }
        .bj{
            background-color: rgba(255,255,255,0.6);
            padding: 15px;
            margin-bottom: 10px;
            border-radius:5px ;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 10px 0 rgba(0, 0, 0, 0.19);            
        }
        .bj a{
            font-size:18px;
        }
        #private{
            position:fixed;
            top: 380px;
            right: 1%;
            z-index: 999;
            width: 20%;
        }
        p{
            height: 30px;
        }
        img{
            width: 32.5%;
        }
        .work  img{
            width: 100%;
        }
       .work{
            width: 32.5%;
            display: inline-block;
            font-size: 18px;
            border: 1px solid #ddd;
            border-radius: 4px;
            text-align: center;
        }
    </style>
    <script>
        function change(name){
            $("body").css("background","url(../static/images/"+name+")");
        }
    </script>
    <title>飞行的火车</title>
</head>
<body onload="lft()">
   <a href="/privatepic"><img id="private" src="../static/images/默契.gif"></a>
   <ul class="nav bg-warning">
            <a class="nav-link text-dark" href="#introduce">简介</a>
            <a class="nav-link text-dark" href="#photo">相册</a>
            <a class="nav-link text-dark" href="#music">音乐</a>
            <a class="nav-link text-dark" href="#program">作品</a>
            <div class="dropdown">
                <a class="btn btn-warning dropdown-toggle" href="#" role="button" id="dropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                一键换肤   
                </a>
                <div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                    <a class="dropdown-item" onclick="change('彩带.png')">皮肤1（彩带）</a>
                    <a class="dropdown-item" onclick="change('多人.png')">皮肤2（人物）</a>
                    <a class="dropdown-item" onclick="change('粉色.jpg')">皮肤3（粉色）</a>
                    <a class="dropdown-item" onclick="change('蝴蝶.png')">皮肤4（蝴蝶）</a>
                    <a class="dropdown-item" onclick="change('宇宙.jpg')">皮肤5（宇宙）</a>
                    <a class="dropdown-item" onclick="change('bg1.png')">重置</a>
                </div>
            </div>
    </ul>
    <div id="demo" class="carousel slide" data-ride="carousel" data-interval="2000">
        <div class="carousel-inner">
            <div class="carousel-item carousel-item-next carousel-item-left">
                <a href="https://code.xueersi.com/live/creator/1?template_project_id=12981814&amp;work_type=xes_classwork&amp;needShare=false&amp;assets_diff=c528df68acf413d62d035636d827ea18">
                    <img src="../static/images/迷宫游戏.png">
                </a>
            </div>
            <div class="carousel-item active carousel-item-left">
                <a href="https://code.xueersi.com/live/creator/1?template_project_id=4230992&amp;work_type=xes_classwork&amp;needShare=false&amp;assets_diff=bbe3b52766f418206968fdf62bd529bb">
                    <img src="../static/images/打字游戏.png">
                </a>
            </div>
        </div>
          <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <div class="carousel-control-prev-icon"></div>
          </a>
          <a class="carousel-control-next" href="#demo" data-slide="next">
            <div class="carousel-control-next-icon"></div>
          </a>
    </div>
    <div class="row" style="margin-top:10px">
        <div class="col-3">
            <div id="introduce" class="bj">
                <img src="../static/images/introduce.png" style="width:100%">
                <h4 class="card-title">码农一枚</h4>
                <p class="card-text">更多功能解锁中...</p>
                <p class="card-text">敬请期待</p>
            </div>
            <div id="music" class="bj">
                <h5 class="card-title">音乐播放器</h5>
                 BGM1:
                <audio controls="controls" style="width:100%" __idm_id__="1060315137">
                    <source src="../static/music/bgm.mp3">
                </audio>
                BGM2:
                <audio controls="controls" style="width:100%" __idm_id__="1060315138">
                    <source src="../static/music/buttercup.mp3">
                </audio>
                BGM2:
                <audio controls="controls" style="width:100%" __idm_id__="1060315139">
                    <source src="../static/music/bgm3.mp3">
                </audio>
            </div>
        </div>
        <div class="col-sm-9">
            <div id="hot" class="bj">
                <h4><span><img src="../static/images/热点.png" style="width:30px"></span>实时热点</h4>
                <ul class="list-group">
                
                     <li class="list-group-item"><a href="http://www.baidu.com/baidu?cl=3&amp;tn=SE_baiduhomet8_jmjb7mjw&amp;rsv_dl=fyb_top&amp;fr=top1000&amp;wd=%B1%B1%BE%A9%BB%A7%BC%AE%C8%CB%BF%DA%B3%F6%C9%FA%CA%FD%B4%B4%CA%AE%C4%EA%D0%C2%B5%CD
">北京户籍人口出生数创十年新低</a></li>
                
                     <li class="list-group-item"><a href="http://www.baidu.com/baidu?cl=3&amp;tn=SE_baiduhomet8_jmjb7mjw&amp;rsv_dl=fyb_top&amp;fr=top1000&amp;wd=%C8%D5%B1%BE%CD%C6%B3%F6%BF%DA%B1%C7%B4%A6%CD%B8%C3%F7%BF%DA%D5%D6
">日本推出口鼻处透明口罩</a></li>
                
                     <li class="list-group-item"><a href="http://www.baidu.com/baidu?cl=3&amp;tn=SE_baiduhomet8_jmjb7mjw&amp;rsv_dl=fyb_top&amp;fr=top1000&amp;wd=%B9%F3%D6%DD%C3%A9%CC%A8%D2%BB%BC%BE%B6%C8%BE%BB%C0%FB139.54%D2%DA%D4%AA
">贵州茅台一季度净利139.54亿元</a></li>
                
                     <li class="list-group-item"><a href="http://www.baidu.com/baidu?cl=3&amp;tn=SE_baiduhomet8_jmjb7mjw&amp;rsv_dl=fyb_top&amp;fr=top1000&amp;wd=%C3%AB%CF%FE%CD%AE%D1%EE%ABW%D4%D9%BA%CF%D7%F7
">毛晓彤杨玏再合作</a></li>
                
                     <li class="list-group-item"><a href="http://www.baidu.com/baidu?cl=3&amp;tn=SE_baiduhomet8_jmjb7mjw&amp;rsv_dl=fyb_top&amp;fr=top1000&amp;wd=%CC%D8%BC%B6%B7%C9%D0%D0%D4%B1%CD%A3%B7%C9%D3%EB%CB%FE%CC%A8%B8%D0%C8%CB%B6%D4%BB%B0">特级飞行员停飞与塔台感人对话</a></li>
                
                </ul>
            </div>
            <div id="program" class="bj">
                <h3><span><img src="../static/images/作品.png" style="width:50px"></span>编程作品</h3>
                    
                    <div class="work">
                        <a href="/uploadwork"><img src="../static/images/作品上传入口.png"></a>
                        <p style="color:red">作品上传</p>
                    </div>
                </div>
                <!--个人相册-->
            <div id="photo" class="bj">
                <h3><span><img src="../static/images/相册.png" style="width:50px"></span>个人相册</h3>
                <div class="card-deck">
                    <div class="card">
                        <img class="card-img-top" src="../static/images/X烟花.png" alt="Card image" style="width:100%">
                        <div class="card-body">
                        <p class="card-text">美丽的烟花难得一见，转瞬即逝。</p>
                        </div>
                    </div>
                    
                    <div class="card">
                        <img class="card-img-top" src="../static/images/X猫.png" alt="Card image" style="width:100%">
                        <div class="card-body">
                        <p class="card-text">这只机灵的小猫是我快乐的源泉。</p>
                        </div>
                    </div>
                    <div class="card">
                        <img class="card-img-top" src="../static/images/X游轮.png" alt="Card image" style="width:100%">
                        <div class="card-body">
                        <p class="card-text">坐着小船，感受星辰大海。</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
  </div>
	<p style="text-align:center;color:black;" align="center"><font size="1">ICP备案号：<a href="https://beian.miit.gov.cn/" valign="top"><font size="1">京ICP备2021035452号</font></a></font></p>
            <div style="width:220px;margin:auto;">
		 		<a href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=11010802037970" style="display:inline-block;text-decoration:none;height:20px;line-height:20px;"><img src="../static/images/备案图标.png" style="width:20px;margin-left:10px;float:left;"><p style="float:left;height:30px;line-height:30px;margin: 0px 0px 0px 5px; color:#939393;"><font size="1">京公网安备 11010802037970号</font></p></a>
            </div>
  


<canvas id="c_n5" width="882" height="902" style="position: fixed; top: 0px; left: 0px; z-index: -1; opacity: 0.7;"></canvas></body></html>
---
layout: single
title: Recent Publications
classes: wide
---
<style>
	/* --- 基本页面样式 (检查是否已存在或冲突) --- */
body {
  margin: 0;
  padding: 0; 
}

html {
  scroll-behavior: smooth; /* 可选: 平滑滚动效果 */
}

/* --- 出版物列表图片/视频预览样式 --- */
.one {
  position: relative; 
  display: inline-block; 
  width: 300px; /* 预览宽度 (请根据需要调整) */
  aspect-ratio: 16 / 9; /* 预览宽高比 (请根据需要调整) */
  overflow: hidden; 
  background-color: #f0f0f0; /* 图片/视频未加载时的背景色 */
}

.two {
  position: absolute; 
  top: 0;
  left: 0;
  right: 0; 
  bottom: 0; 
  opacity: 0; 
  transition: opacity .2s ease-in-out; 
}

.two video { 
    width: 100%;
    height: 100%;
    object-fit: cover; 
}

.one img {
    display: block; 
    max-width: 100%; 
    width: 100%; 
    height: 100%; 
    object-fit: cover; /* 如果图片比例不符会被裁剪 */
    /* object-fit: contain; */ /* 如果不想裁剪但想完整显示图片，可以用这个，可能留白 */
}
/* --- 效果控制结束 --- */

/* --- 年份标题跳转偏移 --- */
h2[id^="publication"], 
h3[id^="year-"] {
  scroll-margin-top: 80px; /* 防止被粘性导航栏遮挡 (请根据导航栏高度调整) */
}
.iconDetails {
	clear: left;
	float:left; 
	width:20%;
    	height:20%;
	max-height:140px;
	max-width:140px; 
} 

.container {
    width:100%;
    height:24%;
    padding:1%;
	margin-bottom: 20px;
}
h4 {
    margin:0px;
}

.button {
    clear: left;
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 4px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 12px;
    margin: 4px 2px;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    cursor: pointer;
}

.green {
    background-color: white; 
    color: black; 
    border: 2px solid #4CAF50;
}

.green:hover {
    background-color: #4CAF50;
    color: white;
}

.blue {
    background-color: white; 
    color: black; 
    border: 2px solid #008CBA;
}

.blue:hover {
    background-color: #008CBA;
    color: white;
}

.red {
    background-color: white; 
    color: black; 
    border: 2px solid #f44336;
}

.red:hover {
    background-color: #f44336;
    color: white;
}

.gray {
    background-color: white;
    color: black;
    border: 2px solid #e7e7e7;
}

.gray:hover {background-color: #e7e7e7;}

.black {
    background-color: white;
    color: black;
    border: 2px solid #555555;
}

.black:hover {
    background-color: #555555;
    color: white;
}
</style>

<script>
function toggleAbstract(btn) {
    var x = btn.nextElementSibling.nextElementSibling;
    if (x.innerHTML === "") {
        x.innerHTML = x.getAttribute("text");
    } else {
        x.innerHTML = "";
    }
}
</script>


My [Google Scholar](https://scholar.google.se/citations?hl=en&user=HgOAYUAAAAAJ) profile.

<h2>References</h2> 
<h2 id="publications" style="scroll-margin-top: 80px; display: inline-block; margin-right: 10px;">Publications</h2> [ <a href="#">Full List</a> ] 
<h3 id="year-2025" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2025</h3>
<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
    <tr onmouseover="iros2025_gripper_start()" onmouseout="iros2025_gripper_stop()" class="publication-entry" data-year="2025" data-topics="softrobotics,deformationestimation"> 
        <td style="padding:16px;width:38%;vertical-align:top;"> 
            <div class="one">
                <div class="two" id="iros2025_gripper_video">
                    <video width=100% height=100% muted autoplay loop>
                        <source src="/images/publications_video/iros2025_gripper.mp4" type="video/mp4"> Your browser does not support the video tag.
                    </video>
                </div>
                <img src='/images/publications_image/iros2025_gripper.jpg' alt="Multimodal Deformation Thumbnail"> 
            </div>
            <script type="text/javascript">
                function iros2025_gripper_start() { document.getElementById('iros2025_gripper_video').style.opacity = "1"; }
                function iros2025_gripper_stop() { document.getElementById('iros2025_gripper_video').style.opacity = "0"; }
                iros2025_gripper_stop();
            </script>
        </td>
        <td style="padding:8px;width:62%;vertical-align:top;"> 
            </td>
    </tr> 

    <tr class="publication-entry" data-year="2025" data-topics="socialrobotics,hri,ux"> 
        <td style="padding:16px;width:38%;vertical-align:top;"> 
            <div class="one">
                 <img src='/images/publications_image/balloon_robot_uist25.jpg' alt="Social Balloon Robot Thumbnail"> 
            </div>
        </td>
        <td style="padding:8px;width:62%;vertical-align:top;"> 
             </td>
    </tr> 
	
</tbody></table>

<h3 id="year-2024" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2024</h3>
<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
    </tbody></table>

<h3 id="year-2023" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2023</h3>
<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
    </tbody></table>

<h3 id="year-2022" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2022</h3>
<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
    </tbody></table>

<h3 id="year-2021" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2021</h3>
<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
    </tbody></table>

<h3 id="year-2020" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2020</h3>
<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
    </tbody></table>
<br style/>



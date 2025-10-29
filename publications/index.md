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
  /* width: 300px; /* 删除或注释掉这一行，让宽度自适应 */
  width: 100%; /* 让 .one 容器填充其父级 td 的可用宽度 */
  max-width: 300px; /* 设定最大宽度，避免图片在超宽屏下过大 */
  /* aspect-ratio: 16 / 9; /* 删除或注释掉这一行，让高度由图片内容决定 */
  height: auto; /* 让高度根据内容自动调整 */
  overflow: hidden; 
  background-color: #f0f0f0; 
  box-sizing: border-box; /* 确保 padding/border 不会增加总宽度 */
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
    object-fit: contain; 
}

.one img {
    display: block; 
    max-width: 100%; 
    width: 100%; 
    height: auto; /* 关键：让高度自动调整以保持图片比例 */
    object-fit: contain; /* 关键：让图片完全包含在容器内，不裁剪，可能留白 */
    /* object-fit: cover; */ /* 如果需要裁剪并填满，则使用这个 */
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
<h2 id="publications" style="scroll-margin-top: 80px; display: inline-block; margin-right: 10px;">Publications</h2> [ <a href="#">Full List</a> ] 
<h3 id="year-2025" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2025</h3>
<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
	<tr class="publication-entry" data-year="2025" data-topics="softrobotics,deformationestimation" data-selected="true"> 
		<td style="padding:16px;width:38%;vertical-align:top;text-align: right;">
			<div class="one">
				<img src='/images/publications_image/iros2025_gripper.jpg' alt="Multimodal Deformation Estimation Thumbnail"> 
			</div>
		</td>
		<td style="padding:8px;width:62%;vertical-align:top;">
			<a href="https://your_domain.com/path/to/paper.pdf"> 
				<span class="papertitle">Multimodal Deformation Estimation of Soft Pneumatic Gripper During Operation</span>
			</a>
			<br>
			<strong>Authors:</strong>Changheng Cai, Fei Xiao, Marcellus Vanzai, Taoyang Wang, Fangbing Zhou, Xuanyang Xu, Jian Zhu<sup>#</sup>, and <b>Yuan Gao</b><sup>#</sup>
			<br>
			<strong>Conference:</strong><em>International Conference on Intelligent Robots and Systems(IROS)</em>, 2025 
			<br>
			<a href="https://your_domain.com/path/to/paper.pdf">[Paper]</a> / 
			<a href="https://github.com/your_username/your_repo">[Code]</a>
			<p></p>
		</td>
	</tr>
	<tr onmouseover="balloon_robot_uist25_start()" onmouseout="balloon_robot_uist25_stop()" class="publication-entry" data-year="2025" data-topics="socialrobotics,hri,ux" data-selected="true"> 
		<td style="padding:16px;width:38%;vertical-align: top;text-align: right;">
			<div class="one">
				<div class="two" id='balloon_robot_uist25_video'>
					<video width=100% height=100% muted autoplay loop>
						<source src="/images/publications_video/balloon_robot_uist25.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>
				<img src='/images/publications_image/balloon_robot_uist25.jpg' alt="Social Balloon Robot Thumbnail">
			</div>
			<script type="text/javascript">
				function balloon_robot_uist25_start() {
					document.getElementById('balloon_robot_uist25_video').style.opacity = "1";
				}
				function balloon_robot_uist25_stop() {
					document.getElementById('balloon_robot_uist25_video').style.opacity = "0";
				}
				balloon_robot_uist25_stop() // 页面加载时默认停止（隐藏）视频
			</script>
		</td>
		<td style="padding:8px;width:62%;vertical-align:top;">
			<a href="https://dl.acm.org/doi/abs/10.1145/3746059.3747666"> 
				<span class="papertitle">Understanding Users' Perceptions and Expectations toward a Social Balloon Robot via an Exploratory Study</span>
			</a>
			<br>
			<strong>Authors:</strong>Chongyang Wang, Tianyi Xia, Yifan Wang, Gang Yu, Zixuan Zhao, Siqi Zheng, Manqiu Liao, Chen Liang, <b>Yuan Gao</b>, Chun Yu<sup>#</sup>, Yuntao Wang, Yuanchun Shi
			<br>
			<strong>Conference:</strong><em>UIST '25: Proceedings of the 38th Annual ACM Symposium on User Interface Software and Technology</em>, 2025 
			<br>
			<a href="https://dl.acm.org/doi/abs/10.1145/3746059.3747666">[Paper]</a> 
			<p></p>
		</td>
	</tr>
	<tr class="publication-entry" data-year="2025" data-topics="nlp,llm,slm,selfreflection" data-selected="true"> 
		<td style="padding:16px;width:38%;vertical-align:top; text-align: right;">
			<div class="one">
				<img src='/images/publications_image/entrospect_acl25.jpg' alt="Entrospect Thumbnail"> 
			</div>
		</td>
		<td style="padding:8px;width:62%;vertical-align:top;"> <a href="https://aclanthology.org/2025.findings-acl.1261/"> 
			<span class="papertitle">Entrospect: Information-Theoretic Self-Reflection Elicits Better Response Refinement of Small Language Models</span>
		</a>
			<br>
			<strong>Authors:</strong>Tianqiang Yan, Ziqiao Lin, Lin Zhang, Zhenglong Sun, <b>Yuan Gao</b><sup>#</sup>
			<br>
			<strong>Conference:</strong><em>Findings of the Association for Computational Linguistics: ACL 2025</em>, 2025 
			<br>
			<a href="https://aclanthology.org/2025.findings-acl.1261/">[Paper]</a> 
			<p></p>
		</td>
	</tr>
	<tr class="publication-entry" data-year="2025" data-topics="droneperception,semisupervisedlearning,knowledgetransfer" data-selected="true"> 
		<td style="padding:16px;width:38%;vertical-align:top;text-align: right;"> 
			<div class="one">
				<img src='/images/publications_image/tits2025_droneperception.jpg' alt="Drone Perception T-ITS Thumbnail"> 
			</div>
		</td>
		<td style="padding:8px;width:62%;vertical-align:top;"> 
			<a href="https://ieeexplore.ieee.org/abstract/document/11005613"> 
				<span class="papertitle">Unlocking Drone Perception in Low AGL Heights: Progressive Semi-Supervised Learning for Ground-to-Aerial Perception Knowledge Transfer</span>
			</a>
        <br>
			<strong>Authors:</strong>Junjie Hu, Chenyou Fan, Mete Ozay, Hua Feng, <b>Yuan Gao</b>, Tin Lun Lam
			<br>
			<strong>Journal:</strong><em>IEEE Transactions on Intelligent Transportation Systems</em>, 2025 
			<br>
			<a href="https://ieeexplore.ieee.org/abstract/document/11005613">[Paper]</a> 
			<p></p>
		</td>
	</tr>
	<tr class="publication-entry" data-year="2025" data-topics="robotics,localization,smrs" data-selected="true"> 
    	<td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
        	<div class="one">
            	<img src='/images/publications_image/icra2025_smrslocalization.jpg' alt="SMSR Localization Thumbnail"> 
            </div>
    	</td>
    	<td style="padding:8px;width:62%;vertical-align:top;"> 
        	<a href="https://ieeexplore.ieee.org/abstract/document/11127871"> 
            	<span class="papertitle">Configuration-Adaptive Visual Relative Localization for Spherical Modular Self-Reconfigurable Robots</span>
        	</a>
        	<br>
        	<strong>Authors:</strong>Yuming Liu, Qiu Zheng, Yuxiao Tu, <b>Yuan Gao</b>, Guanqi Liang, and Tin Lun Lam
        	<br>
       	 	<strong>Conference:</strong><em>2025 IEEE International Conference on Robotics and Automation (ICRA)</em>, 2025 
        	<br>
        	<a href="#">[Paper]</a> 
        <p></p> 
    	</td>
	</tr>
	<tr class="publication-entry" data-year="2025" data-topics="multiagent,selforganization,llm,multimodal" data-selected="true"> 
    <td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
        <div class="one">
            <img src='/images/publications_image/iotj2025_ochmas.jpg' alt="OC-HMAS Thumbnail"> 
            </div>
    </td>
    <td style="padding:8px;width:62%;vertical-align:top;"> 
        <a href="#"> 
            <span class="papertitle">OC-HMAS: Dynamic Self-Organization and Self-Correction in Heterogeneous Multiagent Systems Using Multimodal Large Models</span>
        </a>
        <br>
        <strong>Authors:</strong>Ping Feng, Tingting Yang, Mingyang Liang, Lin Wang, and <b>Yuan Gao</b>
        <br>
        <strong>Journal:</strong><em>IEEE Internet of Things Journal</em>, 2025 
        <br>
        <a href="#">[Paper]</a> 
        <p></p> 
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

















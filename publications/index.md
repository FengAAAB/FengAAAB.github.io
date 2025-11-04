---
layout: single
title: Recent Publications
classes: wide
---
<div class="publications-wrapper">
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
	  max-width: 426px; /* 设定最大宽度，避免图片在超宽屏下过大 */
	  /* aspect-ratio: 16 / 9; /* 删除或注释掉这一行，让高度由图片内容决定 */
	  height: 240px; /* 让高度根据内容自动调整 */
	  overflow: hidden; 
	  background-color: #FFFFFF; 
	  box-sizing: border-box; /* 确保 padding/border 不会增加总宽度 */
	  display: flex; /* 使用 Flexbox 布局 */
	  justify-content: center; /* 水平居中 */
	  align-items: center; /* 垂直居中 */
	}
	.two {
	  position: absolute; 
	  top: 0;
	  left: 0;
	  right: 0; 
	  bottom: 0; 
	  opacity: 0; 
	  transition: opacity .2s ease-in-out; 
		/* 新增：确保 .two 容器也使用Flexbox居中其内容（如果需要的话，但通常GIF会填满） */
	  display: flex;
	  justify-content: center;
	  align-items: center;
	}
	.two video { 
		display: block;
	    width: 100%;
	    height: 100%;
	    object-fit: cover; 
	}
	.one img {
	    display: block; 
	    max-width: 100%; 
	    width: auto;
		max-height: 100%;
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
	.publications-wrapper {
	    padding-left: 80px;  /* 增加左内边距 */
	    padding-right: 80px; /* 同时增加右内边距，保持对称 */
	    /* 如果只想增加左边距，可以只写 padding-left: 40px; */
	    box-sizing: border-box; /* 确保 padding 不会撑大容器 */
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
	<td style="padding:16px;width:100%;vertical-align:middle">
		<p>My <a href="https://scholar.google.se/citations?hl=en&user=HgOAYUAAAAAJ" target="_blank">Google Scholar</a> profile.</p>
		<h2 id="publications" style="scroll-margin-top: 80px;">Publications</h2>
		<p style="margin-top: 5px; margin-bottom: 5px;">
			<span style="font-weight: bold;">Year:</span>
			<a href="#year-2025">2025</a> / 
	        <a href="#year-2024">2024</a> / 
	        <a href="#year-2023">2023</a> / 
	        <a href="#year-2022">2022</a> / 
	        <a href="#year-2021">2021</a> / 
	        <a href="#year-2020">2020</a>
	    </p>
	    <p style="font-size: small; color: #666; margin-bottom: 20px;">
	        (* Equal Contribution, # Corresponding Author)
	    </p>
	<h3 id="year-2025" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2025</h3>
	<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
	<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
		<tr class="publication-entry" data-year="2025" data-topics="softrobotics,deformationestimation" data-selected="true"> 
			<td style="padding:16px;width:25%;vertical-align:top;text-align: right;">
				<div class="one">
					<img src='/images/publications_image/iros2025_gripper.jpg' alt="Multimodal Deformation Estimation Thumbnail"> 
				</div>
			</td>
			<td style="padding:8px;width:75%;vertical-align:top;">
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
		<tr onmouseover="balloon_robot_uist25_gif_start()" onmouseout="balloon_robot_uist25_gif_stop()" class="publication-entry" data-year="2025" data-topics="socialrobotics,hri,ux" data-selected="true"> 
		    <td style="padding:16px;width:25%;vertical-align: top;text-align: right;">
		        <div class="one">
		            <div class="two" id='balloon_robot_uist25_gif'> 
		                <img src="/images/publications_gif/balloon_robot_uist25.gif" style="width:100%; height:100%; object-fit: contain;" alt="Social Balloon Robot Animation"> 
		            </div>
		            <img src='/images/publications_image/balloon_robot_uist25.jpg' alt="Social Balloon Robot Thumbnail">
		        </div>
		        <script type="text/javascript">
		            function balloon_robot_uist25_gif_start() {
		                document.getElementById('balloon_robot_uist25_gif').style.opacity = "1";
		            }
		            function balloon_robot_uist25_gif_stop() {
		                document.getElementById('balloon_robot_uist25_gif').style.opacity = "0";
		            }
		            balloon_robot_uist25_gif_stop(); // 页面加载时默认隐藏 GIF
		        </script>
		    </td>
		    <td style="padding:8px;width:75%;vertical-align:top;">
		        <a href="https://dl.acm.org/doi/abs/10.1145/3746059.3747666"> 
		            <span class="papertitle">Understanding Users' Perceptions and Expectations toward a Social Balloon Robot via an Exploratory Study</span>
		        </a>
		        <br>
		        <strong>Authors:</strong> Chongyang Wang, Tianyi Xia, Yifan Wang, Gang Yu, Zixuan Zhao, Siqi Zheng, Manqiu Liao, Chen Liang, <b>Yuan Gao</b>, Chun Yu<sup>#</sup>, Yuntao Wang, Yuanchun Shi
		        <br>
		        <strong>Conference:</strong><em>UIST '25: Proceedings of the 30th Annual ACM Symposium on User Interface Software and Technology</em>, 2025 
		        <br>
		        <a href="https://dl.acm.org/doi/abs/10.1145/3746059.3747666">[Paper]</a> / 
				<a href="/video/balloon_robot_uist25.mp4" target="_blank">[Video]</a>
		        <p></p>
		    </td>
		</tr>
		<tr class="publication-entry" data-year="2025" data-topics="nlp,llm,slm,selfreflection" data-selected="true"> 
			<td style="padding:16px;width:25%;vertical-align:top; text-align: right;">
				<div class="one">
					<img src='/images/publications_image/entrospect_acl25.jpg' alt="Entrospect Thumbnail"> 
				</div>
			</td>
			<td style="padding:8px;width:75%;vertical-align:top;"> <a href="https://aclanthology.org/2025.findings-acl.1261/"> 
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
			<td style="padding:16px;width:25%;vertical-align:top;text-align: right;"> 
				<div class="one">
					<img src='/images/publications_image/tits2025_droneperception.jpg' alt="Drone Perception T-ITS Thumbnail"> 
				</div>
			</td>
			<td style="padding:8px;width:75%;vertical-align:top;"> 
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
	    	<td style="padding:16px;width:25%;vertical-align:top; text-align: right;"> 
	        	<div class="one">
	            	<img src='/images/publications_image/icra2025_smrslocalization.jpg' alt="SMSR Localization Thumbnail"> 
	            </div>
	    	</td>
	    	<td style="padding:8px;width:75%;vertical-align:top;"> 
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
			<td style="padding:16px;width:25%;vertical-align:top; text-align: right;"> 
				<div class="one">
					<img src='/images/publications_image/iotj2025_ochmas.jpg' alt="OC-HMAS Thumbnail"> 
	            </div>
			</td>
			<td style="padding:8px;width:75%;vertical-align:top;"> 
				<a href="https://ieeexplore.ieee.org/abstract/document/10909066"> 
	            	<span class="papertitle">OC-HMAS: Dynamic Self-Organization and Self-Correction in Heterogeneous Multiagent Systems Using Multimodal Large Models</span>
	        	</a>
	        	<br>
	        	<strong>Authors:</strong>Ping Feng, Tingting Yang, Mingyang Liang, Lin Wang, and <b>Yuan Gao</b>
	        	<br>
	        	<strong>Journal:</strong><em>IEEE Internet of Things Journal</em>, 2025 
	        	<br>
	        	<a href="https://ieeexplore.ieee.org/abstract/document/10909066">[Paper]</a> 
	        	<p></p> 
	    	</td>
		</tr>
	</tbody></table>
	<h3 id="year-2024" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2024</h3>
	<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
	<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
		<tr class="publication-entry" data-year="2024" data-topics="robotics,llm,vlm,perception,reasoning" data-selected="true"> 
	    	<td style="padding:16px;width:25%;vertical-align:top; text-align: right;"> 
	        	<div class="one">
	            	<img src='/images/publications_image/iros2024_liquidperception.jpg' alt="Robot Liquid Perception Thumbnail"> 
	            </div>
	    	</td>
	    	<td style="padding:8px;width:75%;vertical-align:top;"> 
	        	<a href="https://ieeexplore.ieee.org/abstract/document/10801833"> 
	            	<span class="papertitle">Vision-Language Model-based Physical Reasoning for Robot Liquid Perception</span>
	        	</a>
	        	<br>
	        	<strong>Authors:</strong> Wenqiang Lai, Tianwei Zhang, Tin Lun Lam, <b>Yuan Gao</b> 
	        	<br>
	        	<strong>Conference:</strong> <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em>, 2024 
	        	<br>
	        	<a href="https://arxiv.org/pdf/2404.06904">[Paper]</a> 
	        	<p></p> 
	    	</td>
		</tr>
		<tr class="publication-entry" data-year="2024" data-topics="humanoid,robotics,control,walking" data-selected="true"> 
    		<td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
        		<div class="one">
            		<img src='/images/publications_image/arxiv2024_footplacement.jpg' alt="Time-Varying Foot-Placement Control Thumbnail"> 
				</div>
			</td>
			<td style="padding:8px;width:62%;vertical-align:top;"> 
				<a href="https://arxiv.org/abs/2409.08371"> 
					<span class="papertitle">Time-Varying Foot-Placement Control for Underactuated Humanoid Walking on Swaying Rigid Surfaces</span>
				</a>
				<br>
				<strong>Authors:</strong> <b>Yuan Gao</b><sup>*,†</sup>, Victor Paredes<sup>*</sup>, Yukai Gong<sup>†</sup>, Zijian He<sup>†</sup>, Ayonga Hereid<sup>†</sup>, Yan Gu<sup>†</sup> 
				<br>
				<strong>Preprint:</strong> <em>arXiv preprint arXiv:2409.08371</em>, 2024 
				<br>
				<a href="https://arxiv.org/pdf/2409.08371">[Paper]</a> 
				<p></p> 
			</td>
		</tr>
		<tr class="publication-entry" data-year="2024" data-topics="robotics,metarl,inspection,multirobot" data-selected="true"> 
			<td style="padding:16px;width:25%;vertical-align:top; text-align: right;"> 
	        	<div class="one">
	            	<img src='/images/publications_image/icra2024_metarlinspection.jpg' alt="Meta-RL Inspection Thumbnail"> 
	            </div>
	    	</td>
	    	<td style="padding:8px;width:75%;vertical-align:top;"> 
	        	<a href="https://ieeexplore.ieee.org/abstract/document/10610420"> 
	            	<span class="papertitle">Meta-Reinforcement Learning Based Cooperative Surface Inspection of 3D Uncertain Structures using Multi-robot Systems</span>
	        	</a>
	        	<br>
	        	<strong>Authors:</strong> Junfeng Chen, <b>Yuan Gao</b>, Junjie Hu, Fuqin Deng, and Tin Lun Lam
	        	<br>
	        	<strong>Conference:</strong> <em>2024 IEEE International Conference on Robotics and Automation (ICRA)</em>, 2024 
	        	<br>
	        	<a href="https://freeformrobotics.org/wp-content/uploads/2024/03/ICRA24_Chen.pdf">[Paper]</a> 
	        	<p></p> 
	    	</td>
		</tr>
		<tr class="publication-entry" data-year="2024" data-topics="hri,poseestimation,companionrobot,chi" data-selected="true"> 
	    	<td style="padding:16px;width:25%;vertical-align:top; text-align: right;"> 
	        	<div class="one">
	            	<img src='/images/publications_image/chi2024_pepperpose.jpg' alt="PepperPose Thumbnail"> 
	            </div>
	    	</td>
	    	<td style="padding:8px;width:75%;vertical-align:top;"> 
	        	<a href="https://dl.acm.org/doi/full/10.1145/3613904.3642231"> 
	            	<span class="papertitle">PepperPose: Full-Body Pose Estimation with a Companion Robot</span>
	        	</a>
	        	<br>
	        	<strong>Authors:</strong> Chongyang Wang, Siqi Zheng, Lingxiao Zhong, Chun Yu, Chen Liang, Yuntao Wang, <b>Yuan Gao</b>*, Tin Lun Lam, Yuanchun Shi 
	        	<br>
	        	<strong>Conference:</strong> <em>Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems</em>, 2024 
	        	<br>
	        	<a href="https://dl.acm.org/doi/pdf/10.1145/3613904.3642231">[Paper]</a> 
	        	<p></p> 
	    	</td>
		</tr>
		<tr class="publication-entry" data-year="2024" data-topics="robotics,inspectionrobot,pipelinerobot,transformable" data-selected="true"> 
	    	<td style="padding:16px;width:25%;vertical-align:top; text-align: right;"> 
	       		<div class="one">
	            	<img src='/images/publications_image/ral2024_transformablerobot.jpg' alt="Transformable Inspection Robot Thumbnail"> 
	            </div>
	    	</td>
	    	<td style="padding:8px;width:75%;vertical-align:top;"> 
	        	<a href="https://ieeexplore.ieee.org/abstract/document/10508069"> 
	            	<span class="papertitle">Transformable Inspection Robot Design and Implementation for Complex Pipeline Environment</span>
	        	</a>
	        	<br>
	        	<strong>Authors:</strong> Jianlin Wang, Yixiang Wang, Lining Peng, Haixiang Zhang, Hang Gao, Chengjiang Wang, <b>Yuan Gao</b>, Huanliang Luo, Yongquan Chen
	        	<br>
	        	<strong>Journal:</strong> <em>IEEE Robotics and Automation Letters</em>, 2024 
	        	<br>
	        	<a href="https://ieeexplore.ieee.org/abstract/document/10508069">[Paper]</a> 
	        	<p></p> 
	    	</td>
		</tr>
		<tr class="publication-entry" data-year="2024" data-topics="robotics,bipedal,control,stateestimation" data-selected="true"> 
			<td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
				<div class="one">
					<img src='/images/publications_image/report2024_bipedalcontrol.jpg' alt="Time-varying control thumbnail"> 
				</div>
			</td>
			<td style="padding:8px;width:62%;vertical-align:top;"> 
				<a href="https://www.proquest.com/openview/67536fb4c6d715b4b06c328d710159fa/1?pq-origsite=gscholar&cbl=18750&diss=y"> 
					<span class="papertitle">Time-varying control and state estimation for bipedal locomotion</span>
				</a>
				<br>
				<strong>Authors:</strong> <b>Yuan Gao</b>
				<br>
				<strong>Publication:</strong> <em>University of Massachusetts Lowell</em>, 2024 
				<br>
				<a href="#">[Paper]</a> 
				<p></p>
			</td>
		</tr>
	</tbody></table>
		<!--添加23年论文-->
	<h3 id="year-2023" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2023</h3>
	<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
	<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
		<tr class="publication-entry" data-year="2023" data-topics="multirobot,reinforcementlearning,framework,opensource" data-selected="true"> 
		    <td style="padding:16px;width:25%;vertical-align:top; text-align: right;"> 
		        <div class="one">
		            <img src='/images/publications_image/robio2023_multirobolearn.jpg' alt="MultiRoboLearn Thumbnail"> 
		            </div>
		    </td>
		    <td style="padding:8px;width:75%;vertical-align:top;"> 
		        <a href="https://ieeexplore.ieee.org/abstract/document/10354600/"> 
		            <span class="papertitle">MultiRoboLearn: An open-source framework for multi-robot deep reinforcement learning</span>
		        </a>
		        <br>
		        <strong>Authors:</strong> Junfeng Chen, Fuqin Deng, <b>Yuan Gao</b>, Junjie Hu, Xiyue Guo, Guanqi Liang, Tin Lun Lam
		        <br>
		        <strong>Conference:</strong> <em>2023 IEEE International Conference on Robotics and Biomimetics (ROBIO)</em>, 2023 
		        <br>
		        <a href="https://arxiv.org/pdf/2209.13760">[Paper]</a> 
		        <p></p> 
		    </td>
		</tr>	
		<tr class="publication-entry" data-year="2023" data-topics="space,intentioninference,bigru,selfattention" data-selected="true"> 
			<td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
				<div class="one">
					<img src='/images/publications_image/advancesinspace2023_intentioninference.jpg' alt="Intention Inference Thumbnail"> 
				</div>
			</td>
			<td style="padding:8px;width:62%;vertical-align:top;"> 
				<a href="https://www.sciencedirect.com/science/article/pii/S0273117723003101">
					<span class="papertitle">An intention inference method for the space non-cooperative target based on BiGRU-Self Attention</span>
				</a>
				<br>
				<strong>Authors:</strong> Honglin Zhang, Jianjun Luo<sup>†</sup>, <b>Yuan Gao</b><sup>*</sup>, Weihua Ma
				<br>
				<strong>Journal:</strong> <em>Advances in Space Research</em>, 2023 
				<br>
				<a href="https://pdf.sciencedirectassets.com/271642/1-s2.0-S0273117723X00167/1-s2.0-S0273117723003101/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQCVGJVWnS1ZpvM54CS9O1Fi99TuLWipC1%2BnIyfrNTEA2AIhAMYZs28vEO9rO8U5BLto6xUemCCwLB0H0Pttl6E6AubZKrMFCGoQBRoMMDU5MDAzNTQ2ODY1IgzFszJ7FhlfQL1WLhYqkAWyRSw%2Bj85b8irYkQ16ju4aIKME62ROlQFsWNpZidrywbzWvv6Z1sVSsZARQOSIIkj1juQ8fPo7kCm3XIkYiL8GY1tXmwPY8BXsMtXvLMTsNGc2mYlBdq82XOKCDcxV%2FSWFS%2BLYGRoIQKh%2Fkw9xJoJVJLZT2wEd0O0hF%2FhEokLy8t5FKqL17cFQZpaKS%2BfLNaISorWPv%2Fsi6KD3jds%2BnRQc33bPThK4eilMzweG8P4si8y7TcMmrCHusTMjJDR1SJZuCiE2eOhZiVYm5S14G%2BisTNSCI5pLfH68XadENsBpMqoAf8DDm4aW94Jnvw1tIfde7DnH97G7YKUgAwJ4xMkeSZwqgNac34wk9nUTc4Mlp0gxCMu9xjIl0dV7eZMchs8LseBAYyzP2UwwEP%2F%2BgA9q5QAZvhlSk3Qh6CNrIDSxzi%2Frujv0UHGCoj4kVghISvfmNS48T9hxuvJ%2BNN5Fqk5lU7EBHqpHwQY5yv0%2BumgT8ph4mcOjgE3NicVLyKuRQkE67jGfQnaV4eEYStbv8CyB4hWzSzJf6NM7vUDLjo1aVrMKOLxhdONFNRETN8K%2FL7RtPO07dZmax0Q9qAREuWkjrRQ325DfcY%2BfQvs6ouVg8cqZCEgqiR68XRDgjX5v7WRdVwxM3T5DSgij0WJsO61KuMHhSd1JIXILD8lhC7lkFONj2VtcQfjKCbWZ889H%2FpA8xvKZXty%2FmO6713tT3lSYdwS8EgmE%2B6axRwvvcYNsGijrHPBPGAY%2FTYFb5IGEXecPLm%2FhqP392vsK7A6%2Bkmjoid9an2DQC%2FOCRtikN5Qj9kk1APaFZLJ9I0OSh5VH1%2Fi1mqNv5j%2FlRUm%2FL2J49jk9VKkz%2F2kZbCIvaFUNVDXd9DC5pKXIBjqwAdPB%2F3Y6LKPb36YwByFVzBiCGAPA4NOy9GEr4pjxxBdRqkcmaXD%2Fuzd7lRYgJqYMVTgOlEa26l28R5CbpWIKYK17lXjug38xTJWZCuN%2FKmwIOsMB%2Fvzxnm9VFr%2FjVIzIzRu%2Fry2TI9GrOSrOb20VhpHcoVgcS7uKJe4LQvpEFY4tSAflXX4VTfnr%2FZaOnauthUVj3wlvUSUlxRKNaq2zIqaSB0F5okH8Snz9sW0IxHWo&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20251104T023335Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY4WW76TOW%2F20251104%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=d882ccc8b0927b93306a3c6bf0ad6d6f09ee5dcb5840175c744227ed1ee1fa11&hash=3d778f0d66f79ab028420fc6f954c1313eecd44196f8f83692c6ec076cb9e6df&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0273117723003101&tid=spdf-d302cbc8-ea98-43c2-9afc-4863cf195c8c&sid=345998ac52389449b99bf490a7906d7bd696gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=120f5c5a565e0d525254&rr=9990b516691402d2&cc=hk">[Paper]</a> 
				<p></p> 
			</td>
		</tr>
		<tr class="publication-entry" data-year="2023" data-topics="knowledgedistillation,depthestimation,lightweight" data-selected="true"> 
			<td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
				<div class="one">
					<img src='/images/publications_image/ksem2023_depthdistillation.jpg' alt="Depth Distillation Thumbnail"> 
				</div>
			</td>
			<td style="padding:8px;width:62%;vertical-align:top;">
				<a href="https://link.springer.com/chapter/10.1007/978-3-031-40283-8_3">
					<span class="papertitle">Boosting Lightweight Depth Estimation via Knowledge Distillation</span>
				</a>
				<br>
				<strong>Authors:</strong> Junjie Hu, Chenyou Fan, Hualie Jiang, Xiyue Guo, <b>Yuan Gao</b>, Xiangyong Lu, and Tin Lun Lam<sup>#</sup>
				<br>
				<strong>Conference:</strong> <em>International Conference on Knowledge Science, Engineering and Management (KSEM)</em>, 2023 
				<br>
				<a href="https://arxiv.org/pdf/2105.06143">[Paper]</a>
				<p></p>
			</td>
		</tr>
		<tr class="publication-entry" data-year="2023" data-topics="machinelearning,healthcare,annotations" data-selected="true"> 
    		<td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
	        	<div class="one">
	            	<img src='/images/publications_image/tml4h2023_learn2agree.jpg' alt="Learn2Agree Thumbnail"> 
	            </div>
    		</td>
    		<td style="padding:8px;width:62%;vertical-align:top;"> 
        		<a href="https://link.springer.com/chapter/10.1007/978-3-031-39539-0_13"> 
            		<span class="papertitle">Learn2Agree: Fitting with Multiple Annotators Without Objective Ground Truth</span>
        		</a>
        		<br>
        		<strong>Authors:</strong> Chongyang Wang<sup>#</sup>, <b>Yuan Gao</b>, Chenyou Fan, Junjie Hu, Tin Lun Lam, Nicholas D. Lane, and Nadia Bianchi-Berthouze
        		<br>
        		<strong>Conference:</strong> <em>Trustworthy Machine Learning for Healthcare: First International Workshop (TML4H)</em>, 2023 
        		<br>
        		<a href="https://arxiv.org/pdf/2109.03596">[Paper]</a> 
				<p></p> 
			</td>
		</tr>
		<tr class="publication-entry" data-year="2023" data-topics="robotics,localization,rangebased,mechatronics" data-selected="true"> 
			<td style="padding:16px;width:38%;vertical-align:top; text-align: right;">
				<div class="one">
					<img src='/images/publications_image/tmech2023_localization.jpg' alt="Robot Relative Localization Thumbnail">
				</div>
			</td>
			<td style="padding:8px;width:62%;vertical-align:top;">
				<a href="https://ieeexplore.ieee.org/abstract/document/10142210">
					<span class="papertitle">Asymptotically efficient estimator for range-based robot relative localization</span>
				</a>
				<br>
				<strong>Authors:</strong> Yue Wang, Muhan Lin, Xinyi Xie, <b>Yuan Gao</b>, Fuqin Deng, and Tin Lun Lam<sup>#</sup>
				<br>
				<strong>Journal:</strong> <em>IEEE/ASME Transactions on Mechatronics</em>, 2023
				<br>
				<a href="https://freeformrobotics.org/wp-content/uploads/2023/03/TMECH-10-2022-14466.pdf">[Paper]</a> 
				<p></p>
			</td>
		</tr>
		<tr class="publication-entry" data-year="2023" data-topics="robotics,multirobot,selfplay,reinforcementlearning" data-selected="true">
			<td style="padding:16px;width:38%;vertical-align:top; text-align: right;"> 
				<div class="one">
					<img src='/images/publications_image/tro2023_asymmetricselfplay.jpg' alt="Asymmetric Self-Play Thumbnail"> 
            	</div>
   			</td>
    		<td style="padding:8px;width:62%;vertical-align:top;"> 
        		<a href="https://ieeexplore.ieee.org/abstract/document/10101687"> 
            		<span class="papertitle">Asymmetric Self-Play-Enabled Intelligent Heterogeneous Multirobot Catching System Using Deep Multiagent Reinforcement Learning</span>
        		</a>
        		<br>
        		<strong>Authors:</strong> <b>Yuan Gao</b>, Junfeng Chen, Xi Chen, Chongyang Wang, Junjie Hu, Fuqin Deng, and Tin Lun Lam<sup>#</sup>
        		<br>
        		<strong>Journal:</strong> <em>IEEE Transactions on Robotics</em>, 2023 
        		<br>
        		<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10101687">[Paper]</a> 
        		<p></p> 
    		</td>
		</tr>
	</tbody></table>
		<!--添加22年论文-->
	<h3 id="year-2022" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2022</h3>
	<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
	<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
	    </tbody></table>
		<!--添加21年论文-->
	<h3 id="year-2021" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2021</h3>
	<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
	<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
	    </tbody></table>
		<!--添加20年论文-->
	<h3 id="year-2020" style="text-align: left; margin-top: 2em; margin-bottom: 0.5em; scroll-margin-top: 80px;">2020</h3>
	<hr style="border: 0; border-top: 1px solid #eee; margin: 0 0 1em 0;"> 
	<table style="width:100%;border:0px;border-spacing:0px 10px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody> 
	    </tbody></table>
	<br style/>
</div>




















































<template>
    <div class="text">
        <mt-header title="设置" fixed>
        <router-link to="/" slot="left">
        <mt-button icon="back">返回</mt-button>
        </router-link>
        <mt-button icon="more" slot="right"></mt-button>
        </mt-header>
				<div class="mui-scroll-wrapper" style="top:42px;">
					<div class="mui-scroll">
						<ul class="mui-table-view mui-table-view-chevron">
							<li class="mui-table-view-cell mui-media">
								<a class="mui-navigate-right" href="#account">
									<img class="mui-media-object mui-pull-left head-img" id="head-img" src="./img/smile.png" style="border-radius:50%;">
									<div class="mui-media-body">
										Hello MUI
										<p class='mui-ellipsis'>账号:hellomui</p>
									</div>
								</a>
							</li>
						</ul>
						<ul class="mui-table-view mui-table-view-chevron">
							<li class="mui-table-view-cell">
								<a href="#account" class="mui-navigate-right">账号与安全</a>
							</li>
						</ul>
						<ul class="mui-table-view mui-table-view-chevron">
							<li class="mui-table-view-cell">
								<a href="#notifications" class="mui-navigate-right">新消息通知</a>
							</li>
							<li class="mui-table-view-cell">
								<a href="#privacy" class="mui-navigate-right">隐私</a>
							</li>
							<li class="mui-table-view-cell">
								<a href="#general" class="mui-navigate-right">通用</a>
							</li>
						</ul>
						<ul class="mui-table-view mui-table-view-chevron">
							<li class="mui-table-view-cell">
								<a href="#about" class="mui-navigate-right">关于MUI <i class="mui-pull-right update">V3.1.0</i></a>
							</li>
						</ul>
						<ul class="mui-table-view">
							<li class="mui-table-view-cell" style="text-align: center;">
								<a>退出登录</a>
							</li>
						</ul>
					</div>
				</div>
				<input type="text" id="in">
		</div>	

</template>
<script>
    export default{
        data(){
            return {
            }
        }
    }
</script>
<style>
   #in{border-radius:25px;}
</style>

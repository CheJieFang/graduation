<template>
	<div class="Footer">
		<ul class="listFoot">
	        <li>
	            <i class="iconFootTrue">真</i>
	            所有房源实地勘测
	        </li>
	        <li>
	            <i class="iconFootWide">广</i>
	            海量楼盘全面覆盖
	        </li>
	        <li>
	            <i class="iconFootExpert">专</i>
	            专业顾问选址分析
	        </li>
	        <li>
	            <i class="iconFootWhole">全</i>
	            企业服务一站搞定
	        </li>
	    </ul>
		<div><img src="../../img/logo.png"></div>
		<p class="call">
			<span>免费咨询：</span>
			<b>10086</b>
		</p>
			<p>
                ©2015-2018 广州安心租发展有限公司
				<a style="color:#666">京ICP备16019026号</a><br>
				<a  style="color:#666;display:inline-block;">
				    京公网安备 11010802025685号
				</a><br>
				地址：北京市海淀区上地软件园南路57号八维学院
            </p>
	</div>
</template>

<script type="text/javascript">
	export default{
		name: 'Footer',
		data(){
			return {
				test: "Footer"
			}
		},
		methods:{
		},
	}
</script>

<style type="text/css" lang="less" scoped>
@import url('../../styles/main.less');
.Footer{
	background-color: @bg-color;
	// border-top: 1px dashed #ddd;
	// box-shadow: 10px 15px 30px  rgba(0, 0, 0, .4);
	.margin(20,0,0,0);
	img{
		.margin(14,0,0,0);
	}
	ul{
		overflow: hidden;
		border-top: 1px dashed #ddd;
		border-left: 1px dashed #ddd;
		width: 90%;
		.h(102);
		margin:0 auto;
		li{
			    color: #999;
			   	width:50%;
			    .h(50);
			    float: left;
			    .fs(14);
			    text-align: center;
			    color:@color2;
			    .lh(35);
			    .padding(10,0,10,0);
			    border-right: 1px dashed #ddd;
			    border-bottom: 1px dashed #ddd;
		    i{
		    	.fs(20);
		    	.lh(25);
		    	color: red;
		    	font-weight:500;
		    	display: inline-block;
			    width: .70666667rem;
			    height: .70666667rem;
			    vertical-align: text-bottom;
		    }
		}
	}
	div{
		text-align: center;
	}
	.call{
		.margin(14,0,0,0);
		text-align: center; 
		.fs(16);
	}
	p{
		.lh(20);
		// .h(20);
    	color: #666;
    	.fs(12);
    	.margin(14,0,0,0);
    	text-align: center;
	}
}
</style>
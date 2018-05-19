## 打印显示 typing.js



1. 引入文件
	
		<script src="typing.js"></script>

2. 定义一个容器

		<div id="loginBox"></div>

3. 定义需要打印的字符串

		var txt = `<div class="inputBox">
	        <div class="contentBox">
	            <p><b>姓名:</b><input type="text" value="name"><span>!</span></p>
	            <p><b>用户名:</b><input type="text" value="username"><span>!</span></p>
	            <p><b>密码:</b><input type="password" value="password"><span>!</span></p>
	            <p><b>密码:</b><input type="password" value="password"><span>!</span></p>
	            <p><b>邮箱:</b><input type="text" value="e-mail"><span>!</span></p>
	            <p><b>手机号:</b><input type="text" value="phonenumber"><span>!</span></p>
	        </div>
    	</div>`


4. 调用 `typing` 方法

		typing({
			"Tipstext":txt,
			"ContainerId":"loginBox",
			"speed":30
		})
### 调用方式
(```)
	var iframe = document.getElementById('iframe');
	var message = {
		user_id:'1000162639',
		session_id:'8100000212',//会过期，调用时需传有效的session_id
		location:window.locaton.href,
		styles:{
			themeColor:'red',
			boxShadow:"0px 8px 16px 0px rgba(220,20,60, 0.1)",
			buttonStyle:{
		        backgroundImage: "linear-gradient(0deg,black 0%,red 100%),linear-gradient(#ffffff,#ffffff)",
		        backgroundBlendMode: "normal,normal",
		        boxShadow: "0px 8px 16px 0px rgba(220,20,60, 0.45)",
			},
			cancelButton:{
				//定义返回交易按钮的样式
			}
		}
	}
(```)

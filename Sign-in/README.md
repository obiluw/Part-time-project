微信公众号签到活动<br>
//因为从事产品工作后，接触的代码越来越少(给自己越来越水找理由)<br>
//之前开发用的Thinkpad给了侄子..没做好留存,导致做H5自适应异常艰难.<br>
//除此,老旧的JQ库在做新生成DIV的click事件绑定,需要先绑定其现有的父元素,在追踪到需要事件绑定的子节点上<br>

如这段代码<br>
$(".t_in").on("click", '.close', function () {<br>
	$ (".t_in").children().remove();<br>
	$ (".bg,t_wrap").addClass("hide")<br>
});<br>

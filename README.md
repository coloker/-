# -
捕鱼达人
游戏：
	产品设计/策划:
		故事脚本,角色形象
	UI设计:
		形象
	开发:
		OOP
		1. 资源加载
		   图片批量加载，进度 已加载(onload)/要加载总数
		2. 角色抽象  类  实例：
			鱼
				属性：type x y rotate speed cur
				方法: move draw
			炮筒
				属性: type x y rotate cur timer
				方法: draw emit 
			炮弹
				属性: type x y rotate  timer speed
				方法: draw move clear
			金币
				属性：type x y timer
				方法: draw move clear
			渔网
			记分牌
			..
		3. 业务

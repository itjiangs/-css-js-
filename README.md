# resource
a:hover {
	text-decoration: none;
}	

* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	outline: none;
}

#whole1 {
	position: absolute;
	overflow: hidden;
	width: 100%;
	background: #f0f4f6;
}

.whole2 {
	position: relative;
	width: 100%;
	background: #f0f4f6;
	box-sizing: border-box;
	min-height: 100%;
}

.admin_header {
	height: 70px;
	background: #fff;
	box-shadow: 10px 1px 15px rgba(0, 0, 0, .17);
	padding: 0 24px;
	position: fixed;
	z-index: 10;
	width: 100%;
}

.logo {
	float: left;
	height: 80px;
}

.admin_user {
	float: right;
	height: 70px;
	display: flex;
	align-items: center;
	font-size: smaller;
}

.nav1 {
	overflow: hidden;
	width: 220px;
	background: #188ae2;
	height: 100%;
	float: left;
	position: fixed;
	padding-top: 80px;
	padding-bottom: 10px;
	bottom: 0;
	z-index: 9;
}
/*导航栏*/
.accordion {
	width: 216px;
	max-width: 360px;
	margin: 20px auto 20px;
	background: #FFF;
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
}

.accordion .link {
	cursor: pointer;
	display: block;
	padding: 15px 15px 15px 42px;
	color: #4D4D4D;
	font-size: 14px;
	font-weight: 700;
	border-bottom: 1px solid #CCC;
	position: relative;
	-webkit-transition: all 0.4s ease;
	-o-transition: all 0.4s ease;
	transition: all 0.4s ease;
}

.accordion li:last-child .link {
	border-bottom: 0;
}

.accordion li i {
	position: absolute;
	top: 16px;
	left: 12px;
	font-size: 18px;
	color: #595959;
	-webkit-transition: all 0.4s ease;
	-o-transition: all 0.4s ease;
	transition: all 0.4s ease;
}

.accordion li i.fa-chevron-down {
	right: 12px;
	left: auto;
	font-size: 16px;
}

.accordion li.open .link {
	color: #b63b4d;
}

.accordion li.open i {
	color: #b63b4d;
}

.accordion li.open i.fa-chevron-down {
	-webkit-transform: rotate(180deg);
	-ms-transform: rotate(180deg);
	-o-transform: rotate(180deg);
	transform: rotate(180deg);
}

/**
 * Submenu
 -----------------------------*/
.submenu {
	display: none;
	background: #444359;
	font-size: 14px;
}

.submenu li {
	border-bottom: 1px solid #4b4a5e;
}

.submenu a {
	display: block;
	text-decoration: none;
	color: #d9d9d9;
	padding: 12px;
	padding-left: 42px;
	-webkit-transition: all 0.25s ease;
	-o-transition: all 0.25s ease;
	transition: all 0.25s ease;
}

.submenu a:hover {
	background: #b63b4d;
	color: #FFF;
}

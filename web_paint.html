<!DOCTYPE html>
<html>
<head>
	<title>Web Paint</title>
</head>
<script src="./ajax.js" type="text/javascript"></script>
<link href="./style.css" rel="stylesheet" type="text/css">
<body>
	<h1><center>WEB PAINT <img src="paint-palette.png"></center></h1>
	<canvas id="canvas" height=400px width=1000px style="border:1px solid #000000;"></canvas>
	<br>
	<button class="button" onclick="brush()">Brush</button>
	<button class="button" onclick="line()">Line</button>
	<button class="button" onclick="rect()">Rectangle</button>
	<button class="button" onclick="rect_fill()">Rectangle Filled</button>
	<button class="button" onclick="circle()">Circle</button>
	<button class="button" onclick="circle_fill()">Circle Filled</button>
	<button class="button" onclick="ellipse()">Ellipse</button>
	<button class="button" onclick="ellipse_fill()">Ellipse Filled</button>
	<button class="button" onclick="colors()">Colors</button>
	<button class="button" onclick="line_thick()">Line Thickness</button>
	<button class="button" onclick="erase()">Erase</button>
	<button class="button" onclick="clear_canvas()">Clear canvas</button>
	<button class="button" onclick="save_img()">Save image</button>
	<br>
	<div class="colors">
		<button class="button button_red" onclick="Red()">Red</button>
		<button class="button button_blue" onclick="Blue()">Blue</button>
		<button class="button button_yellow" onclick="Yellow()">Yellow</button>
		<button class="button button_green" onclick="Green()">Green</button>
		<button class="button button_black" onclick="Black()">Black</button>
		<button class="button button_brown" onclick="Brown()">Brown</button>
		<button class="button button_violet" onclick="Violet()">Violet</button>
		<button  class="button button_orange"onclick="Orange()">Orange</button>
		<button class="button button_pink" onclick="Pink()">Pink</button>
		<button class="button button_grey" onclick="Grey()">Grey</button>
	</div>
	<div class="thick">
		<button class="button button_1px" onclick="thick_1()">1px</button>
		<button class="button button_3px" onclick="thick_3()">3px</button>
		<button class="button button_5px" onclick="thick_5()">5px</button>
		<button class="button button_8px" onclick="thick_8()">8px</button>
		<button class="button button_10px" onclick="thick_10()">10px</button>
		<button class="button button_14px" onclick="thick_14()">14px</button>
		<button class="button button_16px" onclick="thick_16()">16px</button>
	</div>
	<div>
		<p id="inst"></p>
	</div>
	<div class="link">
	<a href="" id="link" target="_blank">Open drawing</a>
	</div>
<script>
//window.onload=function(){
$(".link").hide();
var canvas=document.getElementById("canvas");
var ctx=canvas.getContext("2d");
ctx.fillStyle="#000000";
ctx.strokeStyle="#000000"
var can_cord = canvas.getBoundingClientRect();
var brush_thick=5;
var brush_t,line_t,rect_t,rectf_t,circle_t,circlef_t,ellipse_t,ellipsef_t;
var erase_t,erase_color;
function disable_fun()
{
	
	brush_t=0;
	line_t=0;
	rect_t=0;
	rectf_t=0;
	circle_t=0;
	circlef_t=0;
	ellipse_t=0;
	ellipsef_t=0;
	erase_t=0;
	if(ctx.fillStyle=="#ffffff")
	{
		ctx.fillStyle="#000000"	;
		ctx.strokeStyle="#000000";
	}
}
function brush(){
	disable_fun();
	brush_t=1;
	canvas.addEventListener('mousedown', onMouseDown, false)
        canvas.addEventListener('mousemove', onMouseMove, false)
        canvas.addEventListener('mouseup', onMouseUp, false)
	document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw."
	canvas.style.cursor="url('paintbrush.png'),auto";
	var mouseX, mouseY, mouseDown = 0,lastX, lastY;
	function draw(ctx,x,y,size) {
	if(brush_t==1){
    		if (lastX && lastY && (x !== lastX || y !== lastY)) {
		        ctx.lineWidth = brush_thick;
        		ctx.beginPath();
		        ctx.moveTo(lastX, lastY);
        		ctx.lineTo(x, y);
		        ctx.stroke();
		}
	  ctx.beginPath();
	  ctx.arc(x, y,brush_thick/2, 0, Math.PI*2, true);
	  ctx.closePath();
	  ctx.fill();
	  lastX = x;
	  lastY = y;
	}
	}
	function onMouseDown() {
		mouseDown = 1
		draw(ctx, mouseX, mouseY, 2)
}

	function onMouseUp() {
	  mouseDown = 0;
	  lastX = 0;
	  lastY = 0;
	}

	function onMouseMove(e) {
	  getMousePos(e)
	  if (mouseDown == 1) {
	      draw(ctx, mouseX, mouseY, 2)
             // canvas.removeEventListener('mousemove',onmove,false);
              //canvas.removeEventListener('mouseup',onmove,false);
              //canvas.removeEventListener('mousedown',onmove,false);
	  }
	}

	function getMousePos(e) {
	  if (!e)
	      var e = event
	  if (e.offsetX) {
	      mouseX = e.offsetX
	      mouseY = e.offsetY
	  }
	  else if (e.layerX) {
	      mouseX = e.layerX
	      mouseY = e.layerY
	  }
	 }
}
function line(){
	disable_fun();
	line_t=1;
        var mx1,my1,mx2,my2;
        document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw a line."
        canvas.style.cursor="crosshair";
        window.addEventListener("mousedown",srt_coord,false);
        function srt_coord(event){
                mx1=event.pageX-can_cord.left;
                my1=event.pageY-can_cord.top;
        }
        window.addEventListener("mouseup",end_coord,false);
        function end_coord(event){
                mx2=event.pageX-can_cord.left;
                my2=event.pageY-can_cord.top;
                //console.log(mx1+" "+my1+" "+mx2+" "+my2);
		if(line_t==1)
		{
	                ctx.beginPath();
			ctx.moveTo(mx1,my1);
			ctx.lineTo(mx2,my2);
                	ctx.stroke();
		}
        }
        return 1
}
function rect(){
	disable_fun();
        rect_t=1;
	var mx1,my1,mx2,my2;
	document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw a rectangle."
	canvas.style.cursor="crosshair";
	window.addEventListener("mousedown",srt_coord,false);
	function srt_coord(event){
		mx1=event.pageX-can_cord.left;
		my1=event.pageY-can_cord.top;
	}
	window.addEventListener("mouseup",end_coord,false);
	function end_coord(event){
                mx2=event.pageX-can_cord.left;
                my2=event.pageY-can_cord.top;
		//console.log(mx1+" "+my1+" "+mx2+" "+my2);
		if(rect_t==1)
		{
		ctx.beginPath();
		//ctx.rect(mx1,my1,Math.abs(mx2-mx1),Math.abs(my2-my1));
		ctx.moveTo(mx1,my1);
		ctx.lineTo(mx1,my2);
		ctx.stroke();
		ctx.beginPath();
		ctx.moveTo(mx1,my1);
                ctx.lineTo(mx2,my1);
		ctx.stroke();
		ctx.beginPath();
		ctx.moveTo(mx1,my2);
                ctx.lineTo(mx2,my2);
		ctx.stroke();
		ctx.beginPath();
		ctx.moveTo(mx2,my1);
                ctx.lineTo(mx2,my2);
	        ctx.stroke();
		}
        }
	return 1
}
function rect_fill(){
	disable_fun();
        rectf_t=1;
        var mx1,my1,mx2,my2;
        document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw a rectangle."
        canvas.style.cursor="crosshair";
        window.addEventListener("mousedown",srt_coord,false);
        function srt_coord(event){
                mx1=event.pageX-can_cord.left;
                my1=event.pageY-can_cord.top;
        }
        window.addEventListener("mouseup",end_coord,false);
        function end_coord(event){
                mx2=event.pageX-can_cord.left;
                my2=event.pageY-can_cord.top;
                //console.log(mx1+" "+my1+" "+mx2+" "+my2);
		if(rectf_t==1)
                {
                ctx.beginPath();
                ctx.rect(mx1,my1,Math.abs(mx2-mx1),Math.abs(my2-my1));
                ctx.fill();
		}
        }
        return 1
}

function circle(){
	disable_fun();
        circle_t=1;
        var mx1,my1,mx2,my2;
        document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw a circle."
	canvas.style.cursor="crosshair";
        window.addEventListener("mousedown",srt_coord,false);
        function srt_coord(event){
                mx1=event.pageX-can_cord.left;
                my1=event.pageY-can_cord.top;
        }
        window.addEventListener("mouseup",end_coord,false);
        function end_coord(event){
                mx2=event.pageX-can_cord.left;
                my2=event.pageY-can_cord.top;
                //console.log(mx1+" "+my1+" "+mx2+" "+my2);
		if(circle_t==1)
		{
                ctx.beginPath();
		var r=Math.abs(Math.sqrt((mx2-mx1)*(mx2-mx1)+(my2-my1)*(my2-my1)))/2
		console.log(mx1+" "+my1+" "+mx2+" "+my2+" "+r);
                ctx.arc((mx1+mx2)/2,(my1+my2)/2,r,0,2*Math.PI);
                ctx.stroke();
		}
		canvas.style.cursor="default";
        }
        return 1
}
function circle_fill(){
	disable_fun();
        circlef_t=1;
        var mx1,my1,mx2,my2;
        document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw a circle."
        canvas.style.cursor="crosshair";
        window.addEventListener("mousedown",srt_coord,false);
        function srt_coord(event){
                mx1=event.pageX-can_cord.left;
                my1=event.pageY-can_cord.top;
        }
        window.addEventListener("mouseup",end_coord,false);
        function end_coord(event){
                mx2=event.pageX-can_cord.left;
                my2=event.pageY-can_cord.top;
                //console.log(mx1+" "+my1+" "+mx2+" "+my2);
		if(circlef_t==1)
		{
                ctx.beginPath();
                var r=Math.abs(Math.sqrt((mx2-mx1)*(mx2-mx1)+(my2-my1)*(my2-my1)))/2
                console.log(mx1+" "+my1+" "+mx2+" "+my2+" "+r);
                ctx.arc((mx1+mx2)/2,(my1+my2)/2,r,0,2*Math.PI);
                ctx.fill();
		}
        }
        return 1
}
function ellipse(){
	disable_fun();
        ellipse_t=1;
        var mx1,my1,mx2,my2;
        document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw a ellipse."
        canvas.style.cursor="crosshair";
        window.addEventListener("mousedown",srt_coord,false);
        function srt_coord(event){
                mx1=event.pageX-can_cord.left;
                my1=event.pageY-can_cord.top;
        }
        window.addEventListener("mouseup",end_coord,false);
        function end_coord(event){
                mx2=event.pageX-can_cord.left;
                my2=event.pageY-can_cord.top;
                //console.log(mx1+" "+my1+" "+mx2+" "+my2);
		if(ellipse_t==1)
		{
                ctx.beginPath();
                var r=Math.abs(Math.sqrt((mx2-mx1)*(mx2-mx1)+(my2-my1)*(my2-my1)))/2
                console.log(mx1+" "+my1+" "+mx2+" "+my2+" "+r);
                ctx.ellipse((mx1+mx2)/2,(my1+my2)/2,r,0.65*r,0,0,2*Math.PI);
                ctx.stroke();
		}
        }
        return 1
}
function ellipse_fill(){
	disable_fun();
        ellipsef_t=1;
        var mx1,my1,mx2,my2;
        document.getElementById("inst").innerHTML="Instructions:<br>Click and drag to draw a ellipse."
        canvas.style.cursor="crosshair";
        window.addEventListener("mousedown",srt_coord,false);
        function srt_coord(event){
                mx1=event.pageX-can_cord.left;
                my1=event.pageY-can_cord.top;
        }
        window.addEventListener("mouseup",end_coord,false);
        function end_coord(event){
                mx2=event.pageX-can_cord.left;
                my2=event.pageY-can_cord.top;
                //console.log(mx1+" "+my1+" "+mx2+" "+my2);
		if(ellipsef_t==1)
		{
                ctx.beginPath();
                var r=Math.abs(Math.sqrt((mx2-mx1)*(mx2-mx1)+(my2-my1)*(my2-my1)))/2
                console.log(mx1+" "+my1+" "+mx2+" "+my2+" "+r);
                ctx.ellipse((mx1+mx2)/2,(my1+my2)/2,r,0.65*r,0,0,2*Math.PI);
                ctx.fill();
		}
        }
        return 1
}


$(".colors").hide();
var toggle1=0;
function colors(){
	if(toggle1%2==0)
	{
		$(".colors").show();
	}
	else
	{
		$(".colors").hide();
	}
	toggle1+=1;
}
function Red(){
	ctx.fillStyle="#FF0000";
	ctx.strokeStyle="#FF0000";
}
function Blue(){
	ctx.fillStyle="#0000FF";
	ctx.strokeStyle="#0000FF";

}
function Yellow(){
        ctx.fillStyle="#FFFF00";
	ctx.strokeStyle="#FFFF00";

}
function Green(){
        ctx.fillStyle="#00FF00";
	ctx.strokeStyle="#00FF00";

}
function Black(){
	ctx.fillStyle="#000000";
	ctx.strokeStyle="#000000";

}
function Brown(){
        ctx.fillStyle="#A52A2A";
	ctx.strokeStyle="#A52A2A";

}
function Violet(){
        ctx.fillStyle="#9400D3";
	ctx.strokeStyle="#9400D3";

}
function Orange(){
        ctx.fillStyle="#FFA500";
	ctx.strokeStyle="#FFA500";

}
function Pink(){
	ctx.fillStyle="#FF1493";
	ctx.strokeStyle="#FF1493";

}
function Grey(){
        ctx.fillStyle="#808080";
	ctx.strokeStyle="#808080";
}
$(".thick").hide();
var toggle2=0;
function line_thick(){
        if(toggle2%2==0)
        {
                $(".thick").show();
        }
        else
        {
                $(".thick").hide();
        }
        toggle2+=1;
}
function thick_1(){
	ctx.lineWidth=1;
	brush_thick=1;
}
function thick_3(){
        ctx.lineWidth=3;
        brush_thick=3;
}

function thick_5(){
        ctx.lineWidth=5;
	brush_thick=5;
}
function thick_8(){
        ctx.lineWidth=8;
	brush_thick=8;
}
function thick_10(){
        ctx.lineWidth=10;
	brush_thick=10;
}
function thick_14(){
        ctx.lineWidth=14;
	brush_thick=14;
}
function thick_16(){
        ctx.lineWidth=16;
	brush_thick=16;
}
function erase(){
	disable_fun();
	erase_t=1;
	ctx.fillStyle="#ffffff"
	ctx.strokeStyle="#ffffff"
	canvas.addEventListener('mousedown', onMouseDown, false)
        canvas.addEventListener('mousemove', onMouseMove, false)
        canvas.addEventListener('mouseup', onMouseUp, false)
	document.getElementById("inst").innerHTML="Instructions:<br>Click 'd' to start painting and 'u' to stop painting."
	canvas.style.cursor="url('paintbrush.png'),auto";
	var mouseX, mouseY, mouseDown = 0,lastX, lastY;
	function draw(ctx,x,y,size) {
	if(erase_t==1){
    		if (lastX && lastY && (x !== lastX || y !== lastY)) {
		        ctx.lineWidth = brush_thick;
        		ctx.beginPath();
		        ctx.moveTo(lastX, lastY);
        		ctx.lineTo(x, y);
		        ctx.stroke();
		}
	  ctx.beginPath();
	  ctx.arc(x, y,brush_thick/2, 0, Math.PI*2, true);
	  ctx.closePath();
	  ctx.fill();
	  lastX = x;
	  lastY = y;
	}
	}
	function onMouseDown() {
		mouseDown = 1
		draw(ctx, mouseX, mouseY, 2)
}

	function onMouseUp() {
	  mouseDown = 0;
	  lastX = 0;
	  lastY = 0;
	}

	function onMouseMove(e) {
	  getMousePos(e)
	  if (mouseDown == 1) {
	      draw(ctx, mouseX, mouseY, 2)
              canvas.removeEventListener('mousemove',onmove,false);
              canvas.removeEventListener('mouseup',onmove,false);
              canvas.removeEventListener('mousedown',onmove,false);
	  }
	}

	function getMousePos(e) {
	  if (!e)
	      var e = event
	  if (e.offsetX) {
	      mouseX = e.offsetX
	      mouseY = e.offsetY
	  }
	  else if (e.layerX) {
	      mouseX = e.layerX
	      mouseY = e.layerY
	  }
	 }
}

function clear_canvas(){
	ctx.clearRect(0,0,canvas.width,canvas.height);
}
function save_img(){
	var img=canvas.toDataURL("image/png");
	console.log("hello");
	$(".link").show();
	document.getElementById("link").href=img
}
</script>
</body>
</html>
	

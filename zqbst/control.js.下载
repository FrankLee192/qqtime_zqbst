function s(id){
    return document.getElementById(id);
}

if(sjbtext.length>0){
	var str = []
	for(var i=0;i<sjbtext.length;i++){
		str.push('<li class="itemda">'+sjbtext[i]+'</li>')
	}
	$('.div_list').eq(0).find('ul').eq(0).prepend(str.join(''))
}
if(lmtit1.length>0){
	var str = []
	lmtit1.forEach(function(c, i){
		str.push(''+c+'')
	})
	$('#cd1').after('<div class="box tjlist"><div class="div_list div_list_c8"><h1><span><a class="cltit">广告推广</a></span></h1><div class="tjlistcn">'+str.join('')+'</div></div></div>')
}


function ShowOrHideAd(id){
	var display="block";
	if(id==0){
		display="block";
		s("acloseoropenad").innerHTML="关闭推广";
		s("acloseoropenad").onclick=function(){ShowOrHideAd(1);}
		$('.itemda').show()
		$('.tjlist').show()
	}
	else{
		display="none";
		s("acloseoropenad").innerHTML="打开推广";
		s("acloseoropenad").onclick=function(){ShowOrHideAd(0);}
		$('.itemda').hide()
		$('.tjlist').hide()
	}
	
	if(s("cd1")!=null && imgac0.length>0){
		s("cd1").innerHTML = imgac0.join("");
		s("cd1").style.display=display;
	}
	/*if(s("cd2")!=null && imgac.length>0) {
		s("cd2").innerHTML = imgac.join("");
		s("cd2").style.display=display;
	}*/
	if(s("cdtop")!=null) {
		s("cdtop").innerHTML = topac.join("");
		s("cdtop").style.display=display;
	}
	if(s("cdlogo")!=null) {
		s("cdlogo").innerHTML = logoac.join("");
		s("cdlogo").style.display=display;
	}
	
	if(s("cd3")!=null && imgac3.length>0){
		s("cd3").innerHTML = imgac3.join("");
		s("cd3").style.display=display;
	}
	if(s("cd4")!=null && imgac4.length>0){
		s("cd4").innerHTML = imgac4.join("");
		s("cd4").style.display=display;
	}
	if(s("cd5")!=null && imgac5.length>0){
		s("cd5").innerHTML = imgac5.join("");
		s("cd5").style.display=display;
	}
	if(s("cd6")!=null && imgac6.length>0){
		s("cd6").innerHTML = imgac6.join("");
		s("cd6").style.display=display;
	}
	if(s("cd7")!=null && imgac7.length>0){
		s("cd7").innerHTML = imgac7.join("");
		s("cd7").style.display=display;
	}
	/*
	if($('.div_list').eq(0).find('h1 div').length>0)
		$('.div_list').eq(0).find('h1 div').html(lmtit1.join(""))
	else
		$('.div_list').eq(0).find('h1').append('<div>'+lmtit1.join("")+'</div>')
	$('.div_list').eq(0).find('h1 div').css("display",display)
	*/
	
	if($('.div_list').eq(1).find('h1 div').length>0)
		$('.div_list').eq(1).find('h1 div').html(lmtit2.join(""))
	else
		$('.div_list').eq(1).find('h1').append('<div>'+lmtit2.join("")+'</div>')
	$('.div_list').eq(1).find('h1 div').css("display",display)
	
	if($('.div_list').eq(2).find('h1 div').length>0)
		$('.div_list').eq(2).find('h1 div').html(lmtit3.join(""))
	else
		$('.div_list').eq(2).find('h1').append('<div>'+lmtit3.join("")+'</div>')
	$('.div_list').eq(2).find('h1 div').css("display",display)
	
	if($('.div_list').eq(3).find('h1 div').length>0)
		$('.div_list').eq(3).find('h1 div').html(lmtit4.join(""))
	else
		$('.div_list').eq(3).find('h1').append('<div>'+lmtit4.join("")+'</div>')
	$('.div_list').eq(3).find('h1 div').css("display",display)
	
	if($('.div_list').eq(4).find('h1 div').length>0)
		$('.div_list').eq(4).find('h1 div').html(lmtit5.join(""))
	else
		$('.div_list').eq(4).find('h1').append('<div>'+lmtit5.join("")+'</div>')
	$('.div_list').eq(4).find('h1 div').css("display",display)
	
	if($('.div_list').eq(5).find('h1 div').length>0)
		$('.div_list').eq(5).find('h1 div').html(lmtit6.join(""))
	else
		$('.div_list').eq(5).find('h1').append('<div>'+lmtit6.join("")+'</div>')
	$('.div_list').eq(5).find('h1 div').css("display",display)
	
	if($('.div_list').eq(6).find('h1 div').length>0)
		$('.div_list').eq(6).find('h1 div').html(lmtit7.join(""))
	else
		$('.div_list').eq(6).find('h1').append('<div>'+lmtit7.join("")+'</div>')
	$('.div_list').eq(6).find('h1 div').css("display",display)
	
	if($('.div_list').eq(7).find('h1 div').length>0)
		$('.div_list').eq(7).find('h1 div').html(lmtit8.join(""))
	else
		$('.div_list').eq(7).find('h1').append('<div>'+lmtit8.join("")+'</div>')
	$('.div_list').eq(7).find('h1 div').css("display",display)
	
	if($('.div_list').eq(8).find('h1 div').length>0)
		$('.div_list').eq(8).find('h1 div').html(lmtit9.join(""))
	else
		$('.div_list').eq(8).find('h1').append('<div>'+lmtit9.join("")+'</div>')
	$('.div_list').eq(8).find('h1 div').css("display",display)
	
	
	
	/*
	if(s("cdtxt1")!=null) {
		s("cdtxt1").innerHTML = lmtit1.join("");
		s("cdtxt1").style.display=display;
	}	
	if(s("cdtxt3")!=null) {
		s("cdtxt3").innerHTML = lmtit3.join("");
		s("cdtxt3").style.display=display;
	}
	if(s("cdtxt4")!=null) {
		s("cdtxt4").innerHTML = lmtit4.join("");
		s("cdtxt4").style.display=display;
	}
	if(s("cdtxt5")!=null) {
		s("cdtxt5").innerHTML = lmtit5.join("");
		s("cdtxt5").style.display=display;
	}	

	if(s("cdtxt2")!=null) {
		s("cdtxt2").innerHTML = lmtit20.join("");
		s("cdtxt2").style.display=display;
	}
	if(s("cdtxttj")!=null) {
		s("cdtxttj").innerHTML = lmtit1.join("");
		s("cdtxttj").style.display=display;
	}		
	if(s("cdtxt13")!=null) {
		s("cdtxt13").innerHTML = lmtit2.join("");
		s("cdtxt13").style.display=display;
	}		
	if(s("cdtxt14")!=null) {
		s("cdtxt14").innerHTML = lmtit3.join("");
		s("cdtxt14").style.display=display;
	}		
	if(s("cdtxt15")!=null) {
		s("cdtxt15").innerHTML = lmtit5.join("");
		s("cdtxt15").style.display=display;
	}
	if(s("cdtxt4")!=null) {
		s("cdtxt4").innerHTML = lmtit4.join("");
		s("cdtxt4").style.display=display;
	}*/
		
	ReplaceAdIni1("cd2");
}

setTimeout("ShowOrHideAd(0)",1000*0);
//window.onerror=function(){return true;} 


function ReplaceAdIni1(id){
	var ul = s(id);
	var spanItem=ul.getElementsByTagName('a');
	var random=function(){return Math.random()>0.5 ? -1 : 1};//为sort()传入的随机排列参数
	var spanArr=new Array();//用来存放元素的数组
	var k,m;
	for(var i=0; i<spanItem.length; i++){
		spanArr.push(spanItem[i]);//将元素存入元素数组
	}
	//spanArr.sort(random);//打乱元素数组排列顺序
	for(k=0; k<spanArr.length; k++){
		ul.appendChild(spanArr[k]);//将打乱后的元素重新插入到页面中
	}
}


var beian = '<span class="beian">工信部备案号：<a href="https://beian.miit.gov.cn/" target="_blank">琼ICP备14002335号-2</a></span>'
$('.copyright').append(beian)
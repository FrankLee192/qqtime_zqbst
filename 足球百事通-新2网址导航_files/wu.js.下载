$(function(){
    /*$(window).scroll(function(){
        var aH = document.body.scrollHeight;
        var jH;
        if (navigator.userAgent.indexOf("Chrome") > -1) {
            jH = document.body.scrollTop;
        } else {
            jH = document.documentElement.scrollTop;
        }            
        var kH = document.body.offsetHeight;            
        var yH = window.screen.availHeight;            
        if(kH -yH - jH < 4){
            //addShow();
        }
    });
    var num=1;
    setInterval(function(){
        if(num<2){              
          $.ajax({
             type: "get",
             url: "/info/item.asp",
             data: "id=10",
             success: function(msg){                   
               $("#mainbox").append(msg);
             }
          });           
          num++;
        }
    },1000);*/
    
	$(".div_list_ns h1 a").each(function(i){
		$(this).hover(function(){
			$(".div_list_ns h1 a").removeClass("on");
			$(this).addClass("on");
			$(".jcbwul").hide();
			$(".jcbwul").eq(i).show();
		});
	});
	
	//text_news
	if($(".side_list").length>0){
		var classid = $(".side_list").attr("classid");
		if(classid==58){
			$(".sdns2").show();
		}
		else if(classid==61){
			$(".sdns1").show();
		}
		else
			$(".sdns3").show();
	}
    
});
function Loading(){
  var mainbox = document.getElementById("mainbox");
  if(mainbox!=null){
    var ullist = mainbox.getElementsByTagName("ul");        
    var li,div,p,a;  
    for(var i=0;i<ullist.length;i++){
      if(ullist[i].id!="tabul_59"&&ullist[i].id!="tabul_58"&&ullist[i].id!="tabul_hot"&&ullist[i].id!="tabul_jcbw"&&ullist[i].id!="tabul_jcbw2"){
        li = ullist[i].getElementsByTagName("li");    
        if (!li._null) {
          for (var i0 = li.length % 7; i0 && i0 != 7; i0++) {
              ullist[i].appendChild(document.createElement('li'));
          }
        }
      }
      
    for(var j=0;j<li.length;j++){
        li[j].onmouseover=function(){
          div = this.getElementsByTagName("div");
          if(div.length>0){
            //判断是否有下拉链接，有则显示
            a = div[0].getElementsByTagName("a");
            if(a.length>0){
              this.className="mosever";
              //a[0].onmouseover=function(){this.className="mosever";}
              for(var k=0;k<a.length;k++){
                a[k].target="_blank";
              }
              if(a.length>10) div[0].className="more";
              div[0].style.display="block";
            }
            /*处理p标记下非链接显示*/          
            p = div[0].getElementsByTagName("p");
            if(p.length>0){
              for(var n=0;n<p.length;n++){
                if(p[n].getElementsByTagName("a").length==0){
                  p[n].style.display="none";
                }
              }
            }
          }
        }
        li[j].onmouseout=function(){
          this.className="";
          div = this.getElementsByTagName("div");
          if(div.length>0){
            div[0].style.display="none";
          }
        }
      }
    }
  }  
}
setTimeout("Loading()",100);

var tabdv24 = document.getElementById("tabdv_25");
if(tabdv24!=null) tabdv24.className="on";

function setTab(cursel){
	var idlist = [25,28];
	setTimeout(function(){			
		for(i=0;i<idlist.length;i++){
			var menu=document.getElementById("tabdv_"+idlist[i]);
			var con=document.getElementById("tabul_"+idlist[i]);
			menu.className=idlist[i]==cursel?"on":"";
			con.style.display=idlist[i]==cursel?"block":"none";
		}
	},100);
}
//JS版的Server.UrlEncode编码函数
function urlEncode(str) 
{ 
    str = str.replace(/./g,function(sHex) 
    { 
        window.EnCodeStr = ""; 
        window.sHex = sHex; 
        window.execScript('window.EnCodeStr=Hex(Asc(window.sHex))',"vbscript"); 
        return window.EnCodeStr.replace(/../g,"%$&"); 
    }); 
    return str; 
} 

function trim(s){return  s.replace(/(^\s*)|(\s*$)/g,  "");} 

function searchkey(){
  //alert(serarch2.myselectvalue[0].value);
  if(GetRadioValue("myselectvalue")==1){
    //serarch2.keyword.value=serarch2.word.value;
    if(trim(serarch2.word.value).length>=2)
      window.location.href="/search/?/"+urlEncode(trim(serarch2.word.value))+"/";
    else
      alert("关键字长度不能为空且必须大于2位");
    return false;
  }else{
    serarch2.action="http://www.baidu.com/baidu";
  }
}
function GetRadioValue(RadioName){
    var obj;    
    obj=document.getElementsByName(RadioName);
    if(obj!=null){
        var i;
        for(i=0;i<obj.length;i++){
            if(obj[i].checked){
                return obj[i].value;            
            }
        }
    }
    return null;
}


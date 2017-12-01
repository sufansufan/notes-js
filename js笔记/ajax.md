### ajax

异步的javascript的x

1.对象

2.打开请求

3.发送请求

4.异步监听

5.操作

```
let  xml = new XMLHttpRequest

xml.open('get','test.txt',true);

xml.send();

xml.onreadystatechange = function(){
	if(xml.readyState == 4){
  		if(xml.statu == 200){
  			documrnt.body.innerHTML +=`<div>${xml.responseText}</div>`
		}
	}
}
```
xml.open('get','data.php?name=pe&age=18&sex=nan',true);



xml.open('post','data.php?name=pe',true);



要设置请求头信息


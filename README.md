## 上海饰的网络科技前端面试题


#### JS题


**1.** 有一个长度未知的数组a，如果它的长度为0就把数字1添加到数组里面，否则按照先进先出的队列规则让第一个元素出队

**2.** console.log('hello'.repeatify(3))
    
   期望打印出hellohellohello

**3.** 如何用person打印出Colin Ihrig

```javascript

	var fullname = 'John Doe'
	var obj = {
		fullname: 'Colin Ihrig',
		getFullname: function() {
		return this.fullname
		}
	}
	 	 
	var person = obj.getFullname
	console.log(obj.getFullname()) // Colin Ihrig
	console.log(person()) // John Doe
	
```

**4.** 不使用loop循环，创建一个长度为100的数组，并且每个元素的值等于它的下标




#### 机试题：
实现要求如下：

![需求](https://github.com/fuliaoyi/showmecode/blob/master/feature.png?raw=true)

  - 通过 vue 去实现   
  - 完整实现需求中的功能逻辑，不需要像素级还原界面   
  - 需求中所提到的 feature 均需实现，所需数据均在 [RSS feed](http://36kr.com/feed) 中   
  - 实现后的页面传到 github 上发给我你的 github 地址即可(发往招聘网站邮箱)



---


*PS：该 RSS 面试题与本公司业务无任何关联，不必担心实现成果被盗取*   
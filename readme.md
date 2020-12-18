01. 用到的知识点
~~~js
1. document.querySelector(`audio[data-key="${e.keyCode}"]`)//通过这种方式获取节点
2. node.classList.add或remove('className')//给节点添加或移除css类
3. audio.currentTime //获取和设置音频当前播放到的时间
4. audio.play()//播放音频
5. 关于audio更多参见MDN
6. 可以给节点添加transitionend事件//注意e.propertyName !== 'transform'的处理
~~~

02. 用到的知识点

~~~js
1. curDate = new Date()//获取当前时间
2. curDate.getSeconds()//获取秒,更多参见MDN
3. node.style.transform = `rotate(${hourDegrees}deg)`//改变节点的style,是行内样式
~~~

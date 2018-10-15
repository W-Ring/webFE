   冒泡：从被触发的事件到document
   捕获：从document到触发的事件
   事件委托：ul li 多个相同的子元素有相同的事件，可以委托给父元素
             涉及到e.target表示，事件冒泡中触发事件的源元素
   阻止默认事件：return false  jQuery中的event.stopPropagation
                            VUE中的事件修饰符v-on:click.prevent
   参考： 事件冒泡、事件捕获、事件委托
          https://blog.csdn.net/juzipidemimi/article/details/73388282
          阻止默认事件，阻止事件冒泡
          https://blog.csdn.net/wxl1555/article/details/53128966

4、万物皆对象，面向对象的编程试以对象为中心，以消息为驱动，所以程序等于对象加消息。对象有三大特性，封装，继承，多态。
封装就是将一些属性和行为抽成一个类，便于复用
继承就是进一步将一类事物共有的属性和行为抽象成一个父类，每一个子类能获取父类的行为和属性，变成自己。
多态就是解耦，解除父子类继承的耦合度

5、5.html

6、
function debounce (fn) {
 let times = null;
return function () {
 if（！tiem） {
  fn.apply (this.arguments)
times = setTimeout(() => { 
  times = null
},500)
}
}
}
function fn2() {
console.log("我是防抖")
}
btn.addEventListener(" click",debounce(fu2))

7、 mysqil_query($link ，‘SELECT * FROM 'device_info' WHERE 'is_connected ' = '1' ’) //不熟悉

8、8.html

9、选第二个

10、
1、单线程
2、非阻塞I/O
3、事件驱动
nodejs超强的高并发能力
实现高性能服务器
开发周期短，开发成本低，学习成本相对较低
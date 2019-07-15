--  基本数据类型
         string number boolean null undefined
 
--  引用数据类型
     普通对象-->object arry RegExp data  math
         函数--> function
 
--  两者区别
         基本数据类型存储在栈内存中，存储信息量较小；
		 引用数据类型存储在堆内存中，存储信息量较大；
		 
--   布尔类型检测为false的五种情况
         0、""、null、undefined、NaN
		 
--   数据类型检测		 
     typeof-->只能检测基本数据类型和函数
	         返回值有6种：string number boolean  undefined  object(普通对象统一返回) function
		      ES6中新添加了一种symbol数据类型
		
 
     instanceof-->检测当前对象是否属于某个类，只能检测引用数据类型
         用法  a instanceof b  true/false   a是否属于b类型 返回值为布尔值
		 
     constrctor-->可检测基本和引用数据类型
	      用法  a.constructor===array  // 返回值为boolean
	 
	 object.prototype.toString.call() 最准确的方法

--   undefined和null的区别
         undefined代表赋值  undefined现在没有，以后也没有；

		 null代表赋值了只是为null  null现在没有，以后会有，占位
		 
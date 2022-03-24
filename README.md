这是百度第二届前端训练营基础班结营考试的个人独立完成作品，  
很幸运通过了基础班的考核进入了进阶班，进阶班的结营项目详见：https://gitee.com/htt-htt/better-me  

题目要求：设计一款H5端餐厅经营小游戏  
角色包含：厨师、顾客、餐厅经营者（用户）   
场景包含：厨房做菜区、餐厅就餐区、顾客等候区  
菜单包含：凉菜、主菜、饮品  

需要实现的功能有：  
1.	每隔一定时间就会有新顾客到达餐厅等候区  
2.	当餐厅有空位时，餐厅经营者引导最先等待的顾客入座点餐  
3.	顾客入座后开始点餐  
4.	点餐完成后，厨房开始做菜，同时点餐顾客开始等待  
5.	厨房做菜完成后，顾客状态变为就餐  
6.	就餐完毕后，结算饭钱，此桌顾客离开  
7.	餐厅经营者可以根据餐厅经营情况招聘厨师和解聘厨师  

约束条件：  
1.	顾客等位时间有上限，到达上限后该顾客离开且当天不再来  
2.	顾客点餐时必须点主菜  
3.	顾客每道菜品等餐时间有上限，当做菜时间超过等餐时间后，该道菜品作废  
4.	当天就餐完毕的顾客当天不再来  
5.	餐厅经营者每周需要给厨师结算工资  
6.	餐厅收入低于招聘厨师花费时无法招聘厨师  

技术点：  
1.	多线程，顾客与顾客之间相互独立，线程同步和异步  
2.	setInterval和setTimeout以及事件监听器的灵活运用  
3.	dom元素的动态生成  
4.	dom元素的css样式的动态修改  


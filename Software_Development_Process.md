# 详细的系统开发过程

## 一、 准备工作

- [x] 1. 增加地区/项目级需要开展评审工作的角色； 增加了地区物资管理角色 
2019-5-10 15:00:13 至 2019-5-10 15:15:01, 用时15分钟


- [X] 2. 对系统中已经有的地区项目进行梳理；  
2019-5-10 15:15:01 至 2019-5-10 16:18:07，用时60分钟；

## 二、正式开发过程
- [ ] 1.  辅助材料月度采购（申请）计划表的开发
2019-5-10 16:21:43 至 2019-5-10 16:58:56，用时37分钟；



## 五、 过程中的问题及思考

### 1. 地区项目的添加问题

- 如果采用现行的组织机构的方式进行地区项目的添加，那就存在一个问题：新的地区/项目增加后，需要调整相关的表单权限，以使得新的地区和项目具有表单的查阅填报等权限，这个过程还是相对比较繁琐的。

- 可以事先建立一些备用地区项目，后期进行修改，但备用的数据总归是有限的，目前备用几个合适呢？超过这个备用数量的时候，就又回到期初的问题了。

- 使用组织机构方式有一个好处，就是指定地区项目的人员可以给予管理部门人员的权限，针对本项目的人员管理会更加方便；

- 目前能想到的一个替代方案是，组织结构下就到地区，然后建立一个人员信息表，表中列具各个地区的人明细及所属项目，填报的权限用数据字段中的所属项目进行控制，但这样的话，报表的权限设置就有些困难了，特别是查看权限不好处理；

- 思考再三，最终还是确认使用组织机构的方式，地区先备用10个，项目部先增加一些，但不被用，后期有需要再进行添加吧。



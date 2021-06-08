---
title: articletest
date: 2021-06-08 11:19:26
tags:
---

func main() {
//定义，c++: int nums[6] = {1,2,3,4}
   //定义一个int数组
var con [6]int
//定义并赋初值
nums := [6]int{1, 2, 3, 4}
   fmt.Println(len(con),len(nums))
//传统遍历数组方式
for i := 0; i <len(nums); i++ {
      fmt.Println("i:", i, "j:", nums[i])
   }
//使用for range遍历
for key, value := range nums {
      fmt.Println(key, value)
   }
}
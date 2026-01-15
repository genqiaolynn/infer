最近在debug这个仓库
1. 直接clone下来就能运行，我把weights和data都放到仓库里了
2. Makefile是修改过的，检查下库的路径就好了
3. make run

文件结构
src
 cpm.hpp 生产者-消费者多线程关系
 infer.cu 推理接口和封装
 infer.hpp 推理接口
 yolo.cuyolo 定义
 yolo.hppyolo 接口和接口
 main.cpp 主函数
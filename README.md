<p align="left">
  <a href [https://github.com/XianYang2547]">
  <img src="https://img.shields.io/badge/Author-@XianYang-000000.svg?logo=GitHub" alt="GitHub"></a>
  
# <p align="center">🍄记录papers🍄
1.一种随机可达的变异搜索机制（智能算法方向）<br>
+ 针对问题：一些经典随机优化算法如遗传算法、差分算法等变异机制存在不足，导致算法全局搜索能力不高，迭代次数、运行时间等指标数值较大。<br>
+ 研究内容：提出一种有效的变异设计机制，即持续存在满足变异概率下子代个体在给定搜索空间内随机可达，进而提高搜索能力和优化精度。<br>
+ 取得结果：通过对比实验得出，该机制可有效提高算法的稳定性，改善搜索能力，同时增加找到最优解的机会，即在后期种群趋同后仍具有跳出局部的能力。<br>

2.基于改进动态域遗传算法的神经元控制器参数优化（控制优化方向）<br>
+ 针对问题：传统遗传算法的选择、交叉与变异操作容易造成算法全局收敛概率低，求解精度不够等问题。<br>
+ 研究内容：提出了一种基于精英策略的动态域十进制整数编码遗传算法。算法以十进制整数编码遗传算法为基础，通过设计包括基因补全变异、重生变异等变异操作以及精英交叉操作，来提高算法的收敛全局性；设计		  搜索变量空间同步与独立动态调整策略，提升算法的收敛精度。<br>
+ 取得结果：仿真函数测试表明算法性能优异，同时该算法用于优化挖掘机伺服系统神经元PID控制参数，取得优良的控制品质，说明算法具有很好的工程适应性。<br>

3.基于改进逐行分类的车道线检测（图像处理方向）<br>
+ 针对问题：基于分割的形状描述对车道线效率低下，YOLO系列检测算法不适用于车道线细长且弯曲的对象。<br>
+ 研究内容：提出一种基于改进行方向的车道线检测方法。选取ResNet作为主干网络，加入了特征金字塔模块用于提取多尺度特征，并使用FTA（Feature Transfer Architecture）模块进行上下文信息的融合。对于车道线实例区分，将实例检测应用于车道线，通过预测热图来检测车道线实例起始点，并回归相对应的一组卷积参数。对于车道线形状预测，采用行分类方法并进行改进。使用逐行位置选择公式来确定车道线的点集，使用车道线在特征图上与真实位置的偏移量来细化每条车道线的形状，降低了FP值。<br>
+ 取得结果：在实验平台上使用Tusimple、CuLane两大基准数据集进行验证，取得了良好的指标与检测效果，实现了对车道线的预测。<br>

学术论文发表：<br>
- [x] 鲜阳,谭飞,李思宇.一种随机可达的变异搜索机制[J].信息技术,2022(06):28-32+38.DOI:10.13274/j.cnki.hdzj.2022.06.006.<br>
- [x] 鲜阳,谭飞.基于改进动态域遗传算法的神经元控制器参数优化[J].组合机床与自动化加工技术,2022(12):36-39+43.DOI:10.13462/j.cnki.mmtamt.2022.12.009.<br>
- [x] 鲜阳,谭飞,尹宋麟.基于改进行方向的车道线检测[J].无线电工程,2023,53(07):1587-1595.<br>
- [x] 尹宋麟,谭飞,周晴，鲜阳.基于改进YOLOv4模型的交通标志检测[J].无线电工程,2022,52(11):2087-2093.<br>

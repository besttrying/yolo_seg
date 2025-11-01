# yolo_seg

##YOLO11
<p align="center">
  <img src="yolo11.png" width=90%> <br>
  Ultralytics YOLO11是一款尖端的、最先进的模型，它在之前YOLO版本成功的基础上进行了构建，并引入了新功能和改进，以进一步提升性能和灵活性。YOLO11设计快速、准确且易于使用，使其成为各种物体检测和跟踪、实例分割、图像分类以及姿态估计任务的绝佳选择。
</p>

<p align="center">
  <img src="tasks.png" width=90%> <br>
  
</p>

结构图如下：
<p align="center">
  <img src="structs.png" width=90%> <br>
  Ultralytics YOLO11是一款尖端的、最先进的模型，它在之前YOLO版本成功的基础上进行了构建，并引入了新功能和改进，以进一步提升性能和灵活性。YOLO11设计快速、准确且易于使用，使其成为各种物体检测和跟踪、实例分割、图像分类以及姿态估计任务的绝佳选择。
</p>

C3K2结构图如下：
<p align="center">
  <img src="c3k2.png" width=90%> <br>
  C3k2，继承自类C2f，其中通过c3k设置False或者Ture来决定选择使用C3k还是Bottleneck.
</p>
<p align="center">
  <img src="backbone.png" width=90%> <br>
</p>
C3PSA结构图如下：
<p align="center">
  <img src="c2psa.png" width=90%> <br>
</p>
分类检测头引入了DWConv（更加轻量级，为后续二次创新提供了改进点），结构图如下（和V8的区别）：
<p align="center">
  <img src="detect.png" width=90%> <br>
</p>

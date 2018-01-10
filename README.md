# drag_and_drop
#### 拖放
**  思路如下:  **
- step1、ondragstart（ 用户开始拖动元素时触发）的时候使用该对象的dataTransfer.setData方法，并且用中间量记录点击的div
- step2、ondragover (当某被拖动的对象在另一对象容器范围内拖动时触发此事件),拖动div的时候阻止拖动的默认事件（drop 事件的默认行为是以链接形式打开）
- step3、ondrop (在一个拖动过程中，释放鼠标键时触发此事件)时候交换两个div的html

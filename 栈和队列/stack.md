# 栈
<h2>栈的定义</h2>
<h6>栈只允许在一端进行插入和删除操作的线性表</h6>
<h6>特点，后进先出</h6>
<h2>栈的操作</h2>
<h6>InitStack(&S)初始化栈</h6>
<h6>DestoryStack(&S)销毁栈</h6>
<h6>Push(&S,x)进栈，如果栈未满，那么将x加入</h6>
<h6>Pop(&S,&x)出栈，弹出栈顶元素，并使用x返回</h6>
<h6>GetTop(S,&x)读栈顶元素，如果栈非空，就返回栈顶元素</h6>
<h6>StackEmpty(S)判断一个栈是否为空，如果为空，则返回true</h6>
<h5>栈的知识点</h5>
<h6>栈的定义和静态顺序表的定义差距在于length和top，然后使top指针指向栈顶元素</h6>
<h6>栈存在两种方式，分别为栈顶指针指向栈顶元素，另一种为栈顶指针指向栈顶元素的下一个位置</h6>
<h6>为了避免资源浪费，我们可以使用共享栈，一个栈top--,另一个栈top++,判断栈满的条件为top1+1 == top2</h6>

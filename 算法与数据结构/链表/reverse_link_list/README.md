我最初的想法跟最快的那个差不多，但是我没有写成这种赋值模式，所以各种报错。
这种赋值其实是一种解包赋值，它相当于保存了现场，再一个萝卜一个坑赋值回去，避免了C语言里赋值操作有先后，粗心一点就会丢失后面节点的尴尬。
所以我这种还使用try来验证输入的做法在Python里根本不需要。
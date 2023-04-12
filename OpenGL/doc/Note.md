1.顶点缓冲区 -> vertex buffer OpenGL的缓冲区，在显卡上面的，也就是显存（VRAM）中
2.着色器 -> 我们需要告诉显卡他需要做什么，这就是着色器
	着色器是一个运行在显卡上的程序，是一对我们可以编写的可以在显卡上运行的代码
OpenGL就是一个状态机
docs.gl
顶点属性：vertex attribute
VertexAttribPointer 告诉OpenGL缓冲区的内存布局
vertex不仅包含了位置，还有texture coordinates, normals, colors, by normasl, tangents...
VertexAttribPointer
	stride:顶点的字节大小
	pointer:指向顶点中的某个属性

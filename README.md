## 1.2 Understanding how it works

![execution](img/1-2.png)

The line printing 'hey hey' is executed before the spawned block. This is because the spawned block is executed asychronously and it doesn't block the thread from executing the following code.
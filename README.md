## Sexist Online Live Debugger's code repo for NDSC 2019

版本控制是非常重要的. 别忘了debug完后运行 `git commit` 和 `git push` ;)

请在这个文件夹下新建一个`file_path.py`文件用来存着所有项目相关的文件夹路径。内容示例：
```python
image_base_folder = "D:/NDSC_2019/images/"
csv_folder = "D:/NDSC_2019/data/"
```
由于每个人都会把文件夹存在不同的路径下，git会自动忽略这个文件，这样我们每个人就可以定义自己电脑上存的路径而不用担心文件会被git覆盖。使用的时候需要在当前文件夹下启动jupyter，这样这个文件才能在notebook里被成功import。更新了这个文件后需要重启kernel才会生效。
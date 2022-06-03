1.首先选择一张图片作为嵌入的对象，确定隐藏的内容学号和ID
2.在github上克隆数字水印代码后，用指令：python3 LSBSteg.py encode -i test.png -o test.png -f info.txt 把info.txt中的内容嵌入了图片test.png中
3.从hide.png中用指令 python3 LSBSteg.py decode -i test.png -o deinfo.txt 提取信息到deinfo.txt中
4.结果正确

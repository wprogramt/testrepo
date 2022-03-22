![QQ图片20220321191443](C:\Users\SHALLOW\Desktop\新建文件夹\QQ图片20220321191443.jpg)



/word     (查找内容，n查找当前光标的下一个关键词，N查找上一个)

:set hlsearch  给查找的关键词高亮

vim ~/.vimrc  预处理的文件，将指令写入文件中可以预处理其他的文件

:n1,n2s/word1/word2/g   从n1行到n2行，s:search  ,将word1全部替换成word2

:n1,n2s/word1/word2/gc 同上 不过每次会让你确认是否要替换


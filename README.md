# crawl.s.data

install
-------
  casperjs依赖 phantomjs 和 python 
  
  nodejs目前只支持python2.6 和 2.7, 如果从源码安装nodejs,则需要要装python 的 2.6或2.7版本. 如果系统安装了更高版本的python,则无法从源码编译安装nodejs,  方便的方法是下载 nodejs的二进制发行包, 并设置环境变量路径即可.
  
>  将下载好的nodejs二进制包解压,并将 bin 目录加入环境变量即可:
>   vi ~/.bashrc
>   在 bashrc 最后加入:  export PATH=/path/nodejs/bin:$PATH
>   执行命令:  source ~/.bashrc   使其生效

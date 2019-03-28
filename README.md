此版本是  https://github.com/OpenSLAM/LearnViORB_NOROS   mac适配后的版本

基于单目的 orb-slam vio 版本吧

依赖  opencv  eigen3  pangolin 等安装 就不详解了

这个项目还依赖一个 cholmod   这个是需要单独安装的
在mac上安装命令：
brew install suite-sparse

其他大体安装过程大体相同吧 直接运行 build.sh 也行

数据路径在ros_vio.cc  main函数 中写死了

运行数据 是Euroc  mav数据
随便下个就好了(下ASL版本,别下bag,bag是ros版本用的)


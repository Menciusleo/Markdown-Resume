 <center>
     <h1>刘汉书</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13329760288
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             tankliu1234@163.com
         </span>


 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 男，1994 年出生
 - 求职意向：C++ 研发工程师

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 学士，武汉大学，电子信息学院，电子信息工程专业，2012.9~2016.7
- 硕士，南京大学，电子科学与工程学院，信号与信息处理专业，2018.9~2021.7
    -南京大学立体成像技术实验室，研究方向：信号降噪
- 通过了 CET4/6 英语等级考试

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **梦幻西游藏宝阁角色数据的爬取**  2019.5

  python爬虫，藏宝阁是网易公司用于游戏角色交易的平台

    具体工作：
    1.多线程爬取所有服务器正在交易的角色信息。
    2.基于单生产者多消费者模型，主线程遍历服务器列表，爬取所有需要爬取的URL，存入队列缓存。开启多个消费者线程，从队列中获取URL，爬取数据并解析。
    3.从IP代理网站爬取代理IP，构建自己的IP池。所有的IP存入mysql数据库并周期性维护。
    4.获取到包含角色数据的JSON文件，从中提取所需的数据，存入数据库。
    5.JSON文件中部分角色数据做了加密处理，破解了加密数据。

- **使用共享内存的方案，实现了一个IPC类，C++实现**  2019.9

    具体工作：
    1.基于共享内存方案实现IPC，可实现多进程间的单向传输。
    2.构建了循环队列用于底层数据存储，利用自旋锁保证数据的安全读写，实现非阻塞。
    3.构建了数据块的block类，读写操作都以block为最小单位。


## <img src="assets/project-diagram-solid.svg" width="30px"> 获奖经历

- 2019年华为杯全国研究生数学建模大赛二等奖


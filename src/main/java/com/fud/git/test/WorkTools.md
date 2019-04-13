###DMS操作：  
&ensp;1,改变数据库数据时,打开DMS,到任务流程,到数据变更;   
&ensp;2,写入SQL,写入更改的标题和描述,选择对应的环境和数据库,然后提交;  
--- 
###部署项目：  
&ensp;工具：Obelisk  
&ensp;步骤：  
&ensp;&ensp;1、【打包任务】到 【新建打包任务】  
&ensp;&ensp;2、 选择分支 然后核对commit id 是否正确  
&ensp;&ensp;3、 选择配置文件 dev 然后确定打包  
&ensp;&ensp;4、 打包完成后 进行【部署】选择要部署的namespace 然后确认部署  
&ensp;&ensp;5、 部署完成后 查看部署情况 获取域名 就可以访问线上swagger
---
###定位BUG：
&ensp;1、【Obelisk3】 选择【部署任务】 【部署情况】的空间 跳转到 挖财云  
&ensp;2、点击【控制台】 进入app_log文件夹 查看文件app.log  vi app.log  
&ensp;3、Shift + G 定位到最后一行 ；  Ctrl + U 上一页  ； Ctrl + D 下一页  
&ensp;4、定位到自己所写代码的位置查看BUG原因      
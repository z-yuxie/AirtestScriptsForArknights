# AirtestScriptsForArknights
使用网易AirtestIDE编写的明日方舟相关自动化脚本

## 肉鸽刷源石锭.air
### 稳定的傀影肉鸽刷源石及蜡烛的自动化脚本
+ 支持羽毛笔、素皮山、时装山这3种干员，且可设置多个干员作为备选，脚本自动判断选择合适的干员进行探索
![image](https://user-images.githubusercontent.com/28329410/171689872-38bb8a13-3b7a-40b6-9b5b-3fc3be922cbe.png)
+ 支持跳过自己的干员列表，直接进行助战招募
![image](https://user-images.githubusercontent.com/28329410/173186124-e3a53c41-0c81-4887-ae28-7b0a94747b1e.png)
+ 支持华为Mate40Pro、MuMu模拟器1440x810分辨率模式这两种机型配置，选定对应机型后，脚本自动加载该机型对应配置进行执行
![image](https://user-images.githubusercontent.com/28329410/171690004-646e1614-0984-448d-bf63-d3ce507c5366.png)
+ 自动收取过关时的源石锭和收藏品，提高积攒源石和基础藏品的效率
![tpl1654944474323](https://user-images.githubusercontent.com/28329410/173186139-16ab2c4c-0b8d-4e04-a81a-5c234cdbc64b.png)
+ 自动识别挑战失败的情况，避免中途失败中断脚本的执行
+ 只刷取肉鸽第一层，快速进行循环挑战
+ 干员配置模板化，只需截取干员在不同界面的标识性截图，并排列成脚本可识别的结构，即可扩展脚本的可用干员列表
![image](https://user-images.githubusercontent.com/28329410/171688631-1fd32e43-b804-410d-a38e-4cca90a2b05f.png)
![image](https://user-images.githubusercontent.com/28329410/171688505-f3c12996-1e01-4d0e-8faa-9abd0f587674.png)
+ 机型配置模板化，只需记录好不同机型的关键坐标点，并排列成脚本可识别的数据结构，即可扩展脚本可支持的机型配置
![image](https://user-images.githubusercontent.com/28329410/171689300-96e67433-1abf-4879-894e-a151c45280ae.png)
+ 战斗关卡过关配置模板化，只需指定干员上场时摆放的位置，并指定关卡的类型，即可扩展脚本可刷取的单人型关卡
![image](https://user-images.githubusercontent.com/28329410/171689523-5b2eed44-b1ed-4a92-a7f5-5b9d1420edca.png)
![image](https://user-images.githubusercontent.com/28329410/171689657-3a80a439-d629-4cae-acf1-2fd7001c8120.png)
![image](https://user-images.githubusercontent.com/28329410/171689776-d9211f27-1bc6-430c-92c4-28df36cf553d.png)

### 屏幕关键坐标点说明
+ 右滑屏幕起始点
![1](https://user-images.githubusercontent.com/28329410/173185902-2633a853-0ddd-40f6-baef-e86148ca3726.png)
![2](https://user-images.githubusercontent.com/28329410/173185883-332afa96-dd4c-4c7a-af53-3d175af144d3.png)
+ 关卡奖励列表的第一个接受按钮
![3](https://user-images.githubusercontent.com/28329410/173185929-758a60cb-72ea-4bbd-ac34-ec6c7f50ac5d.png)
+ 第一个加人入队按钮
![4](https://user-images.githubusercontent.com/28329410/173185912-d967c2eb-f379-457c-91e4-9478902bc901.png)
+ 待入队干员技能选择栏坐标
![5-1](https://user-images.githubusercontent.com/28329410/173185956-cbc2b412-c30b-47cb-8a44-5aa6e4f4d583.png)
![5-2](https://user-images.githubusercontent.com/28329410/173185948-6881e6f0-016b-4f20-a451-fc346710d6da.png)
+ 关卡按钮的可能位置
![6](https://user-images.githubusercontent.com/28329410/173185963-964ad77a-fd36-411f-b0ae-99e391ef800e.png)
+ 干员上场位置（要将干员放置在地图的那个位置上）
![7](https://user-images.githubusercontent.com/28329410/173185973-bfb3b3e0-79fe-41aa-88a5-d04ae1f16c4c.png)
+ 干员朝向位置
![8](https://user-images.githubusercontent.com/28329410/173185984-814c49a8-f690-4389-b4c6-2dccdd19ae5e.png)
+ 干员站场位置（用于开技能）
![9](https://user-images.githubusercontent.com/28329410/173185994-2369e5d5-bf66-4340-a1db-bfabc95d20c2.png)
![10](https://user-images.githubusercontent.com/28329410/173186012-cdf4d617-7aab-407e-aa00-5a7a1529144b.png)
+ 能点到一个或两个选项中最下面的选项的位置（事件中有三个或以上选项的最后一个选项必定带有离开图标）
![11](https://user-images.githubusercontent.com/28329410/173186023-60bf9d26-3b95-4d56-b60e-cd8a58a560ff.png)
![12](https://user-images.githubusercontent.com/28329410/173186031-a056f9c8-68ec-4d44-8209-8ee6a39db479.png)
![13](https://user-images.githubusercontent.com/28329410/173186038-13cd470e-da54-478a-b2ae-c882088d0725.png)



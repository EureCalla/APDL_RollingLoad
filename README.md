# APDL_RollingLoad

### 程式碼核心介紹
🥑 此程式用於建立滾動式負載的結構分析應用模型  
應用示意(不鏽鋼滾輪罩半模型)：
![image](https://github.com/EureCalla/APDL_RollingLoad/blob/main/gif01.gif)
### 應用方法
1. 命名受力區域loadzone
2. 建立一個旋轉中心座標系紀錄它的ID
### Workbench中的命名方式
1. %ARG1%外罩半徑最小值
2. %ARG2%外罩半徑最大值
3. %ARG3%CST直線運輸速度
4. %ARG4%擠壓時面積
5. %ARG5%擠壓時面積寬度
6. %ARG6%求解想轉圈數
7. %ARG7%旋轉座標系ID
8. %ARG8%代表CST分配至滾輪重
9. %ARG9%代表滾輪內應力

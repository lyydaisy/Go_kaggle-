# Go_kaggle-
Go_kaggle 591台北市房屋租金預測競賽檔案

2017.3 
台大，微軟，R-ladies舉辦591台北市房屋租金預測競賽
預測台北市房租

=========================== <br>
租金預測.ipynb -- 清理資料,EDA,建模  <br>
test_code.ipynb -- 預測test租金並提交  <br>
===========================  <br>

處理資料 <br>
1. 有些錯誤的租屋地址導致Google地圖判斷錯誤,因此到捷運站的距離會嚴重失真  <br>
2. 591判定捷運距離方式為直線距離,因此在環河快速道路附近的房子到捷運站的距離會被低估  <br>

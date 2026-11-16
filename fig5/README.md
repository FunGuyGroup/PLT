# Figure 5

在RStudio打开fig5.Rmd并Knit。所有CSV与Rmd放在同一目录；输出PDF、PNG和HTML。

A–C使用原有数据和分析结果。D–E采用Top8统一图例版：每模块最多8条显著通路，FM1为4条；总计60条记录。颜色范围为BH校正P值0–0.05，Count大小范围为2–12，刻度为2、4、6、8、10、12。各模块映射一致。原富集统计值不变，minGSSize仍为10。

kegg_pathways.csv现为Top8实际作图表，含Display_rank及Best_adjusted_P列。原全部通路表及更新前文件已备份至独立核查目录。Rmd兼容UTF-8和GB18030编码的CSV，未修改A–C输入文件。

主要输出：figure5.pdf/png完整图；figure5D、figure5E、figure5DE为更新面板；figure5_BM1至figure5_FM4为模块单图。

#  UMA_ASE_NEB


UMA 是 Meta 的 FAIRCHEM 团队提出的⼀系列通⽤模型，旨在替代传统的密度泛函理论计算，以更快、更准确地预测原⼦系统的能量、⼒、应⼒等物理性质，适⽤于分⼦、材料、催化剂、分⼦晶体等多种化学领域。他的训练集超过了 5 亿个体系，UMA 中的 omol 任务类型，它可以⽤于优化纯粹有机分⼦、⾦属络合物等分⼦体系，其训练集是 OMol25 数据集在 ORCA 中以 ωB97MV/def2-TZVPD 进⾏优化得到的结构训练集。

 ## Features
 - Universal Models for Atoms (UMA)
 - Atomic Simulation Environment (ASE)
 - Nudged Elastic Band (NEB)


## Prerequisite

- Python >=3.12  NEB.py 是在 Python 3.12 环境下测试的。未在更旧版本的 Python 上进行测试，因此可能无法正常运行。
- fairchem-core  使用 pip install fairchem-core 即可完成安装使用 UMA 模型。详细细节见技术说明文档。
- Matplotlib/Numpy 用于绘制训练统计数据和数组操作的科学绘图和数值库。

## Content
<pre>
 File/Folder Name                              Description                                      
---------------------------------------------------------------------------------------------------
 UMA_ASE_NEB                                   目录
  |--Code                                      源码文件夹
  |   |--NEB.py                                NEB代码                 
  |   |--run_uma.sh                            运行bash脚本                         
  |
  |--Example                                   实例文件夹
  |   |--is.xyz                                反应物xyz坐标                           
  |   |--fs.xyz                                产物xyz坐标                        
  |   |--NEB.py                                NEB源码                      
  |   |--run_uma.sh                            运行bash脚本                                                
  |
  |--Manual                                    技术说明文件夹
  |   |--Manual.pdf                            技术说明
</pre>
  

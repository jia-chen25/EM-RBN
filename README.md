## EM-RBN: A Physics-Informed Neural Network Algorithm Based on Integrated Networks and Dynamic Weight Generation    
This branch contains the code for paper: EM-RBN: A Physics-Informed Neural Network Algorithm Based on Integrated Networks and Dynamic Weight Generation  
![](https://github.com/jia-chen25/EM-RBN/blob/master/figure/Integrated%20Networks.png)  
<p align="center">融合网络架构</p>  

![](https://github.com/jia-chen25/EM-RBN/blob/master/figure/Dynamic%20Weight%20Generation.png)  
<p align="center">动态权重生成模块</p>  

### Usage
The usage instructions for this branch are consistent with those in the main branch. Please refer to the main branch documentation for detailed setup and execution guidelines.  
### Benchmarks
The following table shows the performance of EM-RBN compared to Vanilla PINN and PIRBN on a set of benchmark problems. The accuracy is measured in relative $L^{2}$ error between the predicted and true solutions.  
| Benchmark | EM-RBN | PIRBN | Vanilla PINN |
| :-------: | :---: | :----: | :----------: |
| Helmholtz2D($\alpha_{1}=1,\alpha_{2}=8$) | 单元格 | 单元格 |  单元格 |
| Helmholtz2D($\alpha_{1}=6,\alpha_{2}=6$) | 单元格 | 单元格 |  单元格 |  
| Helmholtz2D($\alpha_{1}=1,\alpha_{2}=4$) | 单元格 | 单元格 |  单元格 |
| Helmholtz2D($\alpha_{1}=2,\alpha_{2}=3$) | 单元格 | 单元格 |  单元格 |
| Wave2D | 单元格 | 单元格 |  单元格 |
| Klein–Gordon1D | 单元格 | 单元格 |  单元格 |
| Navier-Stokes | 单元格 | 单元格 |  单元格 |

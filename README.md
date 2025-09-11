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
| Helmholtz2D($\alpha_{1}=1,\alpha_{2}=8$)|$7.45×10^{-3}$|$6.81×10^{-2}$| $1.51$ |
| Helmholtz2D($\alpha_{1}=6,\alpha_{2}=6$) |$6.60×10^{-3}$|$1.05×10^{-2}$| $1.78$ |
| Helmholtz2D($\alpha_{1}=1,\alpha_{2}=4$) |$9.97×10^{-3}$|$3.75×10^{-2}$|$9.59×10^{-2}$ |
| Helmholtz2D($\alpha_{1}=2,\alpha_{2}=3$) |$9.71×10^{-3}$|$3.90×10^{-2}$|$7.98×10^{-2}$ |
| Wave2D | $7.02×10^{-2}$| $2.09×10^{-1}$ | $4.90×10^{-1}$ |
| Klein–Gordon1D | $4.68×10^{-2}$| $9.18×10^{-2}$ | $7.04×10^{-1}$ |
| Navier-Stokes | $2.06×10^{-2}$| $7.02×10^{-2}$ | $1.21×10^{-1}$ |

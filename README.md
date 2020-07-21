# MoS<sub>2</sub> FET

## Introduction

In this project different kinds of models of Field Effect Transistor based on the monolayer materials have been studied and implemented in COMSOL Multiphysics. All the results are compared with the ones presented in the following papers:

[1] Mircea Dragoman, Martino Aldrigo, Mircea Modreanu, and Daniela Dragoman. “Extraordinary tunability of high-frequency devices using Hf<sub>0.3</sub>Zr<sub>0.7</sub>O<sub>2</sub> ferroelectric at very low applied voltages”

[2] Sarah L. Howell, Deep Jariwala, Chung-Chiang Wu, Kan-Sheng Chen, Vinod K. Sangwan, Junmo Kang, Tobin J. Marks, Mark C. Hersam, and Lincoln J. Lauhon. “Investigation of Band-Offsets at Monolayer–Multilayer MoS<sub>2</sub> Junctions by Scanning Photocurrent Microscopy”

[3] Branimir Radisavljevic, Aleksandra Radenovic, Jacopo Brivio, V. Giacometti and Andras Kis. “Single-layer MoS<sub>2</sub> transistors”

[4] Chung-Chiang Wu, Deep Jariwala, Vinod K. Sangwan, Tobin J. Marks, Mark C. Hersam, and Lincoln J. Lauhon. “Elucidating the Photoresponse of Ultrathin MoS<sub>2</sub> Field-Effect Transistors by Scanning Photocurrent Microscopy”

The first model is a transistor with a monolayer and a four layer MoS<sub>2</sub> channel. The results are compared with the simulated ones. This kind on transistor has a single silicon bottom gate. Another transistor that has a bottom and a top gate made of Cr/Au isolated by a layer of hafnium dioxide is studied. This oxide is used to demonstrate a room-temperature single-layer MoS<sub>2</sub> mobility of at least 200 cm<sup>2</sup>V<sup>-1</sup>s<sup>-1</sup>, similar to that of graphene nanoribbons. The last model uses a ferroelectric material, a layer of Hf<sub>0.3</sub>Zr<sub>0.7</sub>O<sub>2</sub> with 6 nm of thickness, instead of the silicon oxide. The ferroeletric material polarization can be reversed by an applied electric field, the polarization is dependent not only on the current electric field but also on its history, giving a hysteresis loop.

For more information please see this [report](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Report.pdf) or this [report in MDPI template](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Report%20MDPI%20template.pdf).

## COMSOL Models
### MoS<sub>2</sub> FET with bottom gate 
![](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/monolayer_model.png)
* [Monolayer MoS<sub>2</sub> FET](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/monolayer_mos2_only_semi.mph)
* [4 Layer MoS<sub>2</sub> FET](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/4L%20MoS2%20FET_only_semi.mph)

### MoS<sub>2</sub> FET with bottom and top gate
![](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/HfO2_fabrication.png)
![](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/HfO2_model.png)
* [MoS<sub>2</sub> + HfO<sub>2</sub> FET](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/MoS2_HfO2_transistor_only_semi.mph) 
* [MoS<sub>2</sub> + Hf<sub>0.3</sub>Zr<sub>0.7</sub>O<sub>2</sub> FET](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Zirconio.mph) 

## Results
Here are shown some (not all) results, for more information about the results please see this [report](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Report.pdf) or this [report in MDPI template](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Report%20MDPI%20template.pdf).

The dotted lines are those simulated with COMSOL, the solid ones are those reported in the papers.

Monolayer MoS<sub>2</sub> FET I<sub>d</sub>(V<sub>d</sub>):

![](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Grafici/MATLAB/MoS2_monolayer/monolayer_Id(Vd).png)

4 Layer MoS<sub>2</sub> FET I<sub>d</sub>(V<sub>d</sub>):

![](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Grafici/MATLAB/MoS2_4Layer/4layer_Id(Vd).png)

MoS<sub>2</sub> + HfO<sub>2</sub> FET I<sub>d</sub>(V<sub>ds</sub>) varying V<sub>tg</sub>:
![](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Grafici/MATLAB/MoS2_HfO2/Id(Vds)_HfO2_MoS2_varying_Vtg.png)

MoS<sub>2</sub> + HfO<sub>2</sub> + Hf<sub>0.3</sub>Zr<sub>0.7</sub>O<sub>2</sub> FET I<sub>d</sub>(V<sub>ds</sub>) varying V<sub>tg</sub>:
![](https://github.com/MatteoOrlandini/MoS2-FET/blob/master/Grafici/MATLAB/HfZrO2/HfZrO2_Id(Vds)_varying_Vtg.png)


## References
[1] Mircea Dragoman, Martino Aldrigo, Mircea Modreanu, and Daniela Dragoman. “Extraordinary tunability of high-frequency devices using Hf<sub>0.3</sub>Zr<sub>0.7</sub>O<sub>2</sub> ferroelectric at very low applied voltages”

[2] Sarah L. Howell, Deep Jariwala, Chung-Chiang Wu, Kan-Sheng Chen, Vinod K. Sangwan, Junmo Kang, Tobin J. Marks, Mark C. Hersam, and Lincoln J. Lauhon. “Investigation of Band-Offsets at Monolayer–Multilayer MoS<sub>2</sub> Junctions by Scanning Photocurrent Microscopy”

[3] Branimir Radisavljevic, Aleksandra Radenovic, Jacopo Brivio, V. Giacometti and Andras Kis. “Single-layer MoS<sub>2</sub> transistors”

[4] Chung-Chiang Wu, Deep Jariwala, Vinod K. Sangwan, Tobin J. Marks, Mark C. Hersam, and Lincoln J. Lauhon. “Elucidating the Photoresponse of Ultrathin MoS<sub>2</sub> Field-Effect Transistors by Scanning Photocurrent Microscopy”

<h1 align="center">
 An Integrated Programmable CPG with Bounded Output
</h1>

<div align="center">

V. Pasandi, H. Sadeghian, M. Keshmiri, D. Pucci, "An Integrated Programmable CPG with Bounded Output" in IEEE Transactions on Automatic Control (TACON), 2022

</div>

<p align="center">


https://user-images.githubusercontent.com/34647611/170982775-a75f0b8c-c685-4559-b70f-fc99c90fc868.mp4



 
<div align="center">
IEEE Transactions on Automatic Control, 2022
</div>

<div align="center">
  <a href="https://ieeexplore.ieee.org/document/9756235"><b>Paper</b></a> |
  <a href="https://arxiv.org/abs/2204.07766#:~:text=Cyclic%20motions%20are%20fundamental%20patterns,cyclic%20motions%20in%20robotic%20applications"><b>Pre-print</b></a> |
  <a href="https://www.youtube.com/watch?v=WG_TlM6lt-8"><b>Video</b></a> |
 <a href="Results"><b>Results</b></a>
</div>

## Abstract

Cyclic motions are fundamental patterns in robotic applications including industrial manipulation and legged robot locomotion. This paper proposes an approach for the online
modulation of cyclic motions in robotic applications. For this purpose, we present an integrated programmable Central Pattern Generator (CPG) for the online generation of the reference joint trajectory of a robotic system out of a library of desired periodic motions. The reference trajectory is then followed by the lower-level controller of the robot. The proposed CPG generates a smooth reference joint trajectory convergence to the desired one while preserving the position and velocity joint limits of the robot. The integrated programmable CPG consists of one novel bounded output programmable oscillator. We design the programmable oscillator for encoding the desired multidimensional periodic trajectory as a stable limit cycle. We also use the state transformation method to ensure that the oscillator’s output and its first-time derivative preserve the joint position and velocity limits of the robot. With the help of Lyapunov based arguments, We prove that the proposed CPG provides global stability and convergence of the desired trajectory. The effectiveness of the proposed integrated CPG for trajectory  generation is shown in a passive rehabilitation scenario on the Kuka iiwa robot arm, and also in walking simulation on a seven-link bipedal robot.

## Results
:warning: **The results is work in progress!**

## Citing this work

If you find the work useful, please consider citing:

```bibtex
@article{pasandi2022integrated,
  title={An Integrated Programmable CPG with Bounded Output},
  author={Pasandi, Venus and Sadeghian, Hamid and Keshmiri, Mahdi and Pucci, Daniele},
  journal={IEEE Transactions on Automatic Control},
  year={2022},
  publisher={IEEE}
  doi={10.1109/TAC.2022.3166715}
}

```

### Maintainer

This repository is maintained by:

| | |
|:---:|:---:|
| [<img src="https://github.com/VenusPasandi.png" width="80">](https://github.com/VenusPasandi) | [@VenusPasandi](https://github.com/VenusPasandi) |

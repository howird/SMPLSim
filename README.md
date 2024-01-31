[Repo still under construction]
# Porting of UHC and PHC to MUJOCO>=3

`smpl_sim` is a pip-installable library containing a modelization of the SMPL humanoid in different simulators (MUJOCO and Isaac Gym). It is a minimal library to support simple humanoid tasks, and is the basis library for doing more complicated tasks such as motion imitation. 

### Commands:

```
python examples/env_humanoid_test.py headless=False
python smpl_sim/run.py env=speed
python smpl_sim/run.py env=getup
python smpl_sim/run.py env=reach

```

Authors: [@Zhengyi](https://github.com/ZhengyiLuo)  [@Matteo](https://github.com/teopir)


## Citation
If you find this work useful for your research, please cite our paper:
```
@inproceedings{Luo2023PerpetualHC,
    author={Zhengyi Luo and Jinkun Cao and Alexander W. Winkler and Kris Kitani and Weipeng Xu},
    title={Perpetual Humanoid Control for Real-time Simulated Avatars},
    booktitle={International Conference on Computer Vision (ICCV)},
    year={2023}
}            
```

Also consider citing these prior works that are used in this project:

```
@inproceedings{Luo2022EmbodiedSH,
  title={Embodied Scene-aware Human Pose Estimation},
  author={Zhengyi Luo and Shun Iwase and Ye Yuan and Kris Kitani},
  booktitle={Advances in Neural Information Processing Systems},
  year={2022}
}


@inproceedings{rempeluo2023tracepace,
    author={Rempe, Davis and Luo, Zhengyi and Peng, Xue Bin and Yuan, Ye and Kitani, Kris and Kreis, Karsten and Fidler, Sanja and Litany, Or},
    title={Trace and Pace: Controllable Pedestrian Animation via Guided Trajectory Diffusion},
    booktitle={Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2023}
}     

@inproceedings{Luo2021DynamicsRegulatedKP,
  title={Dynamics-Regulated Kinematic Policy for Egocentric Pose Estimation},
  author={Zhengyi Luo and Ryo Hachiuma and Ye Yuan and Kris Kitani},
  booktitle={Advances in Neural Information Processing Systems},
  year={2021}
}
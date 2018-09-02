# prg_QuadrotorPapers
All papers and resources related to Quadrotor Research.

## Quadrotor basics
- [**Our own CMSC828T course**](https://cmsc828t.github.io)
- [**Vijay Kumar's UPenn course**](https://alliance.seas.upenn.edu/~meam620/wiki/index.php)
- [**Daniel Mellinger's Thesis**](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1705&context=edissertations)
- [**UZH's Quadrotor Tutorial**](https://github.com/uzh-rpg/rpg_quadrotor_control/blob/master/documents/theory_and_math/theory_and_math.pdf)

## Quadrotor Trajectory Generation
- [**Minimum Snap Trajectory**](http://www-personal.acfr.usyd.edu.au/spns/cdm/papers/Mellinger.pdf): Kumar's Minimum Snap trajectory generator. [Code](https://github.com/ethz-asl/mav_trajectory_generation)
- [**Polynomial trajectory planning for aggressive quadrotor flight in dense indoor environments**](https://pdfs.semanticscholar.org/8c76/f1add88df14c59f75818952beaa1ec69f62a.pdf):  Nicholas Roy's MIT trajectory generator. [Code](https://github.com/ethz-asl/mav_trajectory_generation)
- [**A computationally efficient motion primitive for quadrocopter trajectory generation**](https://flyingmachinearena.org/wp-content/publications/2015/mueTRO15.pdf): Raffaello D’Andrea's trajectory generator. [Code](https://github.com/ethz-asl/mav_trajectory_generation)
- [**Search-based Motion Planning for Aggressive Flight in SE(3)**](https://arxiv.org/pdf/1710.02748.pdf): Kumar's aggressive motion planning, can go through a forest aggressively. [Code](https://github.com/sikang/mpl_ros)


## Quadrotor Controls
- [Design of Decoupling and Nonlinear PD Controller for Cruise Control of a Quadrotor](https://arxiv.org/pdf/1708.04584.pdf). Aug 2017.
- [Modelling and control of quadcopter](http://sal.aalto.fi/publications/pdf-files/eluu11_public.pdf), Teppo Luukkonen. (2011)
- [Aggressive Quadrotor Flight through Narrow Gaps with Onboard Sensing and Computing using Active Vision](http://rpg.ifi.uzh.ch/doczercs/ICRA17_Falanga.pdf), Falanga, David Scaramuzza et al, (ICRA 2017). [Supplementary video](http://rpg.ifi.uzh.ch/aggressive_flight.html)
- N. Michael, D. Mellinger, Q. Lindsey, and V. Kumar, “The GRASP multiple micro UAV testbed,” IEEE Robot. Autom. Mag., vol. 17, no. 3, pp. 56–65, Sep. 2010.
- M. Faessler, F. Fontana, C. Forster, and D. Scaramuzza, “Automatic reinitialization and failure recovery for aggressive flight with a monocular vision-based quadrotor,” in Proc. IEEE Int. Conf. Robot. Autom., 2015, pp. 1722–1729.
- D. Mellinger, N. Michael, and V. Kumar, “Trajectory generation and control for precise aggressive maneuvers with quadrotors,” Int. J. Robot. Res., vol. 31, no. 5, pp. 664–674, 2012.
- M. Hehn and R. D’Andrea, “A frequency domain iterative learning algorithm for high-performance, periodic quadrocopter maneuvers,” J. Mechatronics, vol. 24, no. 8, pp. 954–965, 2014. 

#### LQR Controller:
- [PID, LQR and LQR-PID on a quadcopter platform](http://ieeexplore.ieee.org/document/6572698/), Lucas M. Argentim et al. (2013)
- [Multi-Agent Testbed development, modelling and control of Quadrotor UAVs](http://kth.diva-portal.org/smash/get/diva2:551115/FULLTEXT01.pdf). p.p. 27-31, KTH Thesis. (2012)
- [Comparison of PID and LQR controllers on a quadrotor helicopter](http://www.naun.org/main/UPress/saed/2015/a442014-074.pdf), Demet Canpolat Tosun et al. (2015)
- [LQR- MIT Reference, A Good Theoritical Proof](https://ocw.mit.edu/courses/mechanical-engineering/2-154-maneuvering-and-control-of-surface-and-underwater-vehicles-13-49-fall-2004/lecture-notes/lec19.pdf), MIT. 


## Odometry and Sensor Fusion
### Visual Odometry/Visual SLAM
### Visual Inertial Odometry/VI SLAM
- [**Visual-Inertial-Aided Navigation for High-Dynamic Motion in Built Environments Without Initial Conditions**](https://ieeexplore.ieee.org/document/6092505/): Sukkarieh's first paper on VIO using a Pre-Integrated factor. [Code](https://bitbucket.org/gtborg/gtsam)
- [**IMU Preintegration on Manifold for Efficient Visual-Inertial Maximum-a-Posteriori Estimation**](https://www.cc.gatech.edu/~dellaert/ftp/Forster15rss.pdf): Scaramuzza's VIO paper for pre-integration on Manifold, used in project Tango. [Code](https://bitbucket.org/gtborg/gtsam)
- [**The Battle for Filter Supremacy: A Comparative Study of the Multi-State Constraint Kalman Filter and the Sliding Window Filter**](https://ieeexplore.ieee.org/document/7158317/): Lee Clement's awesome comparsion paper. [Code](https://github.com/utiasSTARS/msckf-swf-comparison)
- [**Iterated extended Kalman filter based visual-inertial odometry using direct photometric feedback**](http://journals.sagepub.com/doi/10.1177/0278364917728574): ETH-Z ROVIO paper. Works like a charm. [Code](https://github.com/ethz-asl/rovio)
- **MSCKF based Monocular VIO**: Kostas' Implementation of MSKF based monocular VIO used in EVIO paper. [Code](https://github.com/daniilidis-group/msckf_mono)
- [**VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator**](https://arxiv.org/pdf/1708.03852.pdf): Shaojie's awesome VIO code. [Code](https://github.com/HKUST-Aerial-Robotics/VINS-Mono)
- [**A Benchmark Comparison of Monocular Visual-Inertial Odometry Algorithms for Flying Robots**](http://rpg.ifi.uzh.ch/docs/ICRA18_Delmerico.pdf): Scaramuzza's great comparison of SVO, MSCKF, OKVIS, ROVIO and VINS on different computers: Laptop, Intel NUC, Up Board and ODROID. 

### Stereo Visual Odometry/Stereo Visual SLAM
### RGB-D Odometry/RGB-D SLAM
### LIDAR Odometry/LIDAR SLAM

## Quadrotor going through Window

## Quadrotor Carrying Payload

## Event based Quadrotor

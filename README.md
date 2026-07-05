# Robotics & State Estimation (RiSE) Tutorials

## Philosophy

> Math lasts forever, even in the AI era.
>
> The best way to attack Math is to write it down and think twice yourself.

## Motivation

This course is designed to cover the in-depth math knowledge essential for research in **Robotics & State Estimation**, with direct applications to:

- Robot perception and navigation
- Simultaneous Localization and Mapping (**SLAM**)
- Structure from Motion (**SfM**)
- Visual-Inertial Odometry (**VIO**)
- Multi-sensor fusion & calibration

## Outline

| # | Topic | Instructor | Notes |
|:-:|---|---|:-:|
| 1 | Basics: probability, linear algebra, linear systems                          | Yulin Yang | [PDF](lectures/lecture_latex/rise_notes.pdf) |
| 2 | Rotation, Lie / quaternion, translation, SE(3), SE<sub>2</sub>(3)            | Yulin Yang | [PDF](lectures/lecture_latex/rise_notes.pdf) |
| 3 | Camera model, triangulation, calibration, point / line / plane               | Yulin Yang | [PDF](lectures/lecture_latex/rise_notes.pdf) |
| 4 | Information vs. covariance, marginalization & Schur complement, VO/SLAM pipeline, estimator design, EKF from MAP | Yulin Yang | [PDF](lectures/lecture_latex/rise_notes.pdf) |
| 5 | IMU model & noise discretization, IMU integration / preintegration (discrete, ACI²/CPI), mean & covariance propagation on SO(3) and SE<sub>2</sub>(3) | Yulin Yang | [PDF](lectures/lecture_latex/rise_notes.pdf) |
| 6 | Kalman filter and batch least squares, marginalization, null space           | Yulin Yang | — |
| 7 | State formulation (global-centric, invariant, robocentric, equivariant…)     | Chuchu Chen | — |
| 8 | Kalman-filter-based VINS, optimization-based, observability analysis         | Chuchu Chen | — |
| 9 | IMU pre-integration-based VINS, multi-IMU                                    | Yulin Yang | — |
| 10 | Learning-based SLAM / Dense Mapping                                         | Xingxing Zuo | — |

## Reference Reading

See [`resources/`](resources/README.md) for the full reading list and links.

**Lecture 2 — rotation, Lie groups, SE(3), quaternions**
- Barfoot, *State Estimation for Robotics*, Cambridge Univ. Press, 2017 — Ch. 7 (matrix Lie groups): <http://asrl.utias.utoronto.ca/~tdb/bib/barfoot_ser17.pdf>
- Dellaert et al., *Lie Groups for 2D and 3D Transformations* (GTSAM): <https://github.com/borglab/gtsam/blob/develop/doc/LieGroups.pdf>
- Atanasov, *Rotations SO(3) and Rigid-Body Motions SE(3)* (ECE276A, UCSD, 2020): <https://natanaso.github.io/ece276a2020/ref/ECE276A_12_SO3_SE3.pdf>
- Solà, Deray & Atchuthan, *A Micro Lie Theory for State Estimation in Robotics*, 2018: <https://arxiv.org/abs/1812.01537>
- Trawny & Roumeliotis, *Indirect Kalman Filter for 3D Attitude Estimation*, UMN TR 2005-002 — Sec. 1: <https://mediawiki.isr.tecnico.ulisboa.pt/images/d/db/Indirect_Kalman_Filter_for_3D_Attitude_Estimation.pdf>
- Solà, *Quaternion Kinematics for the Error-State Kalman Filter*, 2017 — Sec. 1–3: <https://arxiv.org/abs/1711.02508>

## Course Logistics

- **One lecture per week.**
- Bring a pen and paper — follow along with the equation derivations.
- Video recordings and notes are shared after each lecture. **Please do not redistribute (e.g., to YouTube) for now.**
- Discussions and office hours are held on GitHub: <https://github.com/yangyulin/rise-tutorial/discussions>

## Course Time

Weekly on **Sunday**:

| Location      | Local time              |
|---------------|-------------------------|
| Seattle       | 6:30 AM – 7:45 AM PDT   |
| Washington DC | 9:30 AM – 10:45 AM EDT  |
| Abu Dhabi     | 5:30 PM – 6:45 PM       |
| Beijing       | 9:30 PM – 10:45 PM      |

## Contact

- **[Yulin Yang](https://yangyulin.net/)** — <yangyulin1@gmail.com>
- **[Chuchu Chen](https://chuchuchen.net/)** — <chuchu.chen@gwu.edu>
- **[Xingxing Zuo](https://xingxingzuo.github.io/)** — <xingxing.zuo@mbzuai.ac.ae>

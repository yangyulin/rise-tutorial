# Resources — reference reading list

Background references for the RiSE lectures. These are **third-party works**, so the
PDFs are **not committed** to this repo (copyright + repo size); use the official links
below. Each entry notes the relevant section. A matching BibTeX entry lives in
`lectures/lecture_latex/libraries/extras.bib`.

> To fetch local copies (gitignored) into this folder, see the download commands at the
> bottom of this file.

## Lecture 2 — rotation, Lie groups, SE(3), quaternions

| Reference | Relevant part | Link |
|---|---|---|
| Barfoot, *State Estimation for Robotics*, Cambridge Univ. Press, 2017 | Ch. 7 — matrix Lie groups | <http://asrl.utias.utoronto.ca/~tdb/bib/barfoot_ser17.pdf> |
| Dellaert et al., *Lie Groups for 2D and 3D Transformations* (GTSAM) | whole | <https://github.com/borglab/gtsam/blob/develop/doc/LieGroups.pdf> |
| Atanasov, *Rotations SO(3) and Rigid-Body Motions SE(3)* (ECE276A, UCSD, 2020) | whole | <https://natanaso.github.io/ece276a2020/ref/ECE276A_12_SO3_SE3.pdf> |
| Trawny & Roumeliotis, *Indirect Kalman Filter for 3D Attitude Estimation*, UMN TR 2005-002 | Sec. 1 — quaternion algebra | <https://mediawiki.isr.tecnico.ulisboa.pt/images/d/db/Indirect_Kalman_Filter_for_3D_Attitude_Estimation.pdf> |
| Solà, *Quaternion Kinematics for the Error-State Kalman Filter*, 2017 | Sec. 1–3 | <https://arxiv.org/abs/1711.02508> · <https://www.iri.upc.edu/people/jsola/JoanSola/objectes/notes/kinematics.pdf> |

## Fetch local copies (gitignored)

```bash
cd resources
curl -L -o trawny_indirect_kf_3d_attitude.pdf "https://mediawiki.isr.tecnico.ulisboa.pt/images/d/db/Indirect_Kalman_Filter_for_3D_Attitude_Estimation.pdf"
curl -L -o gtsam_lie_groups.pdf "https://github.com/borglab/gtsam/raw/develop/doc/LieGroups.pdf"
curl -L -o atanasov_ece276a_so3_se3.pdf "https://natanaso.github.io/ece276a2020/ref/ECE276A_12_SO3_SE3.pdf"
curl -L -A "Mozilla/5.0" -o sola_quaternion_kinematics.pdf "https://arxiv.org/pdf/1711.02508"
# Barfoot: download from the author's page (link above)
```

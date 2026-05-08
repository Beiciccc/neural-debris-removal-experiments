# Experiment Records

This file tracks public submission outcomes and lightweight candidate statistics. Lower public score is better for this competition.

## Public Submission Results

| Date UTC | File | Description | Status | Public Score |
|---|---|---|---:|---:|
| 2026-04-30 20:54:57.137000 | `sub01_baseline_it20_lr1e4_thr020.csv` | sub01 baseline finetune it20 lr1e-4 thr0.2 | COMPLETE | 266.5512 |
| 2026-04-30 21:01:28.143000 | `sub02_baseline_it20_scale095_drop020.csv` | sub02 baseline it20 confidence scale 0.95 drop <=0.2 | COMPLETE | 260.8718 |
| 2026-05-01 04:53:06.653000 | `sub03_post_scale093_drop020_from_sub01.csv` | sub03 postprocess sub01 confidence scale 0.93 drop <=0.2 | COMPLETE | 259.1262 |
| 2026-05-01 04:55:05.233000 | `sub04_post_scale090_drop020_from_sub01.csv` | sub04 postprocess sub01 confidence scale 0.90 drop <=0.2 | COMPLETE | 257.9011 |
| 2026-05-02 16:23:25.423000 | `sub05_zaoui_public_prune015_ewc50.csv` | sub05 zaoui public prune0.15 ewc50 | COMPLETE | 250.0711 |
| 2026-05-02 16:25:14.090000 | `sub06_zaoui_public_scale095_drop020.csv` | sub06 zaoui public scale0.95 drop0.20 | COMPLETE | 250.5126 |
| 2026-05-03 22:13:01.900000 | `sub08_zaoui_prune0125_real_ewc50.csv` | sub08 zaoui prune0.125 ewc50 | COMPLETE | 251.1680 |
| 2026-05-03 22:14:32.763000 | `sub09_zaoui_public_scale102_keep020.csv` | sub09 zaoui public scale1.02 keep0.20 | COMPLETE | 249.8820 |
| 2026-05-05 07:53:30.730000 | `sub10_zaoui_public_scale103_drop020.csv` | sub10 zaoui public scale1.03 drop0.20 | COMPLETE | 249.8118 |
| 2026-05-05 07:55:30.277000 | `sub11_zaoui_public_scale105_keep020.csv` | sub11 zaoui public scale1.05 keep0.20 | COMPLETE | 249.7103 |
| 2026-05-06 04:27:40.807000 | `sub12_zaoui_public_scale106_keep020.csv` | sub12 zaoui public scale1.06 keep0.20 | COMPLETE | 249.6699 |
| 2026-05-06 04:29:30.987000 | `sub13_zaoui_public_scale107_keep020.csv` | sub13 zaoui public scale1.07 keep0.20 | COMPLETE | 249.6356 |
| 2026-05-07 23:01:32.353000 | `sub14_zaoui_public_scale108_keep020.csv` | sub14 zaoui public scale1.08 keep0.20 | COMPLETE | 249.6019 |
| 2026-05-07 23:04:48.417000 | `sub15_zaoui_public_scale109_keep020.csv` | sub15 zaoui public scale1.09 keep0.20 fixed-empty | COMPLETE | 249.5749 |

## Candidate Direction Notes

- Confidence scaling on the Zaoui public-pruning candidate improved the public score from scale 1.02 through 1.09.
- Best recorded public score in this snapshot is 249.5749 from `sub15_zaoui_public_scale109_keep020.csv`.
- Later candidate files are retained as generated artifacts for follow-up submissions.

# AphasiaRecoveryCohort

| Date     | Task                             | Notes                                                                                                              |
|----------|----------------------------------|--------------------------------------------------------------------------------------------------------------------|
| 10/14/24 | Extracted .mat data to csv       | There is no ‘aal’ atlas for ‘dti’. No 'dit' and 'rest' for participant 1047, 1080.                                 |
| 10/14/24 | Combined csv to a single csv     | In POLAR_measures, 1032 and 1084 have multiple entries.                                                            |
| 10/15/24 | Ran LR, SVR, RF for baseline     | R = 0.02, 0.26, 0.48. Looks like models are outputing a constant range, which is expected with so many dimensions. |
| 10/23/24 | Ran MLP, CNN                     | R = 0.26, 0.35                                                                                                     |
| 10/23/24 | Change input to 3D, ran CNN, GCN | R = 0.33, -0.05. Models work better for 3D input. Preliminary results not good. Need to tune configurations.       |

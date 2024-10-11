
_____________________________________________________________
config
  |
  |--- comparator
  |
  |--- current_cycle
  |
  |--- n_cycles
  |
  |--- alpha_spend
  |
  |--- options
  |       |--- Set_A
  |       |       |--- subgroups
  |       |       |--- covariates
  |       |       |--- tests
  |       |       |--- maxSPRT
  |       |               |--- sample_size
  |       |               |--- D
  |       |               |--- M
  |       |               |--- R0
  |       |               |--- tailed
  |       |               |--- alpha_spend_type
  |       |
  |       |--- Set_B
  |       |       ...
  |       ...
  |
  |--- results
  |       |--- cycle_1
  |       |       |--- test (e.g. O-E)
  |       |       |           |--- Set_A --- `data.table()`
  |       |       |           |--- Set_B --- `data.table()`
  |       |       |           ...
  |       |       |--- test (e.g. PmaxSPRT)
  |       |       |           |--- Set_A --- `data.table()`
  |       |       |           |--- Set_B --- `data.table()`
  |       |       |           ...
  |       |       ...
  |       |
  |       |--- cycle_2
  |       |       ...
  |       ...
  |
  |--- maxSPRT_datastore
  |       |--- Set_A
  |       |       |--- setup
  |       |       |--- alpha_spend
  |       |       |--- subgroup/covariate combo 1
  |       |       |       |--- subgroup_definition
  |       |       |       |--- summary
  |       |       |       |--- p_old
  |       |       |
  |       |       |--- subgroup/covariate combo 2
  |       |       |       |--- subgroup_definition
  |       |       |       |--- summary
  |       |       |       |--- p_old
  |       |       ...
  |       |
  |       |--- Set_B
  |       |       ...
  |      ...
  ___________________________________________________________


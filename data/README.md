# Data

The data files are **not included** in this repository. They were provided for a course exam and are not redistributed here.

The analysis expects two CSV files in this folder:

| File | Rows | Description |
|---|---|---|
| `midterm_all_data.csv` | 849 | Every player with at least one target in the 2018–2020 NFL seasons |
| `midterm_focus_data.csv` | 23 | A subset of players used for visual comparisons |

Both files have the same three columns:

| Column | Description |
|---|---|
| `player_id` | Anonymised player identifier |
| `num_events` | Number of receptions (catches) |
| `num_trials` | Number of targets (passes thrown to the player) |

The underlying statistics come from the [`nflfastR`](https://www.nflfastr.com/) package. You can rebuild a similar dataset by aggregating receptions and targets per receiver from `nflfastR` play-by-play data.

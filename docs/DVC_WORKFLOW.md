# DVC Workflow Documentation

## Remote Configuration
A local folder remote named myremote was configured:
~/dvc-remote-storage

## Dataset Versioning
DVC was used to track the Iris dataset.

Version 1: 150 rows
Version 2: 170 rows

## Workflow Followed

1. dvc add - Track the dataset.
2. git add - Stage the DVC metafile.
3. git commit - Save dataset version information.
4. dvc push - Upload dataset to DVC remote.

## Dataset Comparison
The command dvc diff was used to compare dataset versions.

## Dataset Restoration
The commands git checkout and dvc checkout
were used to restore historical dataset versions.

Version 1 was restored with 150 rows.
Version 2 was restored with 170 rows.

## Conclusion
DVC successfully managed dataset versioning
and Git integration for reproducible ML experiments.
# DVC Workflow

DVC was installed and initialized in the Git repository.

A local folder was configured as the DVC remote.

The Iris dataset was generated and tracked using DVC.

Version 1 contained 150 rows.

20 synthetic rows were added to create Version 2
containing 170 rows.

The dataset versions were compared using dvc diff.

Previous dataset versions were restored using
git checkout and dvc checkout.

The workflow used was:

dvc add → git add → git commit → dvc push

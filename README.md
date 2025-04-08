# Job Artifacts

The output of a job or the assets generated by a job are called job artifacts.

In Github Actions, we can either download these files and use them manually or we can download and use them automatically in other jobs. We can have a subsequent jobs that would do something with the output of the current job.

Artifacts -> https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts

# Outputs

Apart from files and assets, there may be outputs from jobs like simple values that we might want to use on subsequent jobs.

ex: dates, hashes, random values ...

Outputs -> https://docs.github.com/en/actions/using-jobs/defining-outputs-for-jobs

# Context Values

Context Values -> https://docs.github.com/en/actions/learn-github-actions/contexts

# PiLL #
## Pipeline for LOFAR LBA ##
Parset for the genericpipeline to do the initial steps of the LOFAR LBA calibration.
Now only the calibrator part of the pipeline is available.

The script LBA_pipeline.py automatically creates the pipeline.cfg and clusterdesc file and is replacing the directories of the pipeline.parset in a convenient way (for single node use only).
If you do not use LBA_pipeline.py make sure that the plugins folder is properly listed in your pipeline.cfg.
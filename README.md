CMS_Iaas_demo
=============


- Step 1: Setup ``CMSSW_14_1_0_pre0`` in a proper file system location. Do `cmsenv`
- Step 2: Pull a root file from DAS ttbar dataset, or feed a file into `miniaod_2023_cfg.py`
.. code-block:: bash
  dataset=/TTto2L2Nu_HT-500_NJet-7_TuneCP5_13p6TeV_powheg-pythia8/Run3Summer23DRPremix-130X_mcRun3_2023_realistic_v14-v3/AODSIM
- Step 3: run the `run.py` with arguments
.. code-block:: bash
  cmsRun run.py sonic=True address=<server IP address> port=<grpc port> 

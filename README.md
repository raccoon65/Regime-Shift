# Regime-Shift
detecting changes of regime form samples
Experiment
step1: create input for behavioral and MRI session in exp/input
>>createInputs_shift(subID)
>>createInputs_shift_mri(subID)
ex: createInputs_shift_mri('test')

step2: run behavior session in exp folder
>>run_regime_shift_behavior(subID,blockNo)
ex: run_regime_shift_behavior(‘test’,1)

step3: run MRI session in exp folder
>>run_regime_shift_fmri(subID,blockNo)

Data
Meaning for each column
Block/trial/observation/reaction time/estimation number/reward amount

Analysis
Analyze parameters for each subject
>>analyze_shift_allsubj

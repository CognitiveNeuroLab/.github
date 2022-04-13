[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<br />
<p align="center">
  <a href="https://github.com/CognitiveNeuroLab/Index_overview_CNL">
    <img src="image/logo.jpeg" alt="Logo" width="286" height="120">
  </a>

  <h3 align="center">Indexing CNL github</h3>

  <p align="center">
    Indexing for the CNL github


**Table of Contents **
  
1. [How to keep this index up-to-date](#how-to-keep-this-index-up-to-date)
    - [Who should add to this index](#who-should-add-to-this-index)
    - [When to add to this index](#when-to-add-to-this-index)
    - [How to add to this index](#how-to-add-to-this-index)  
2. [Index](#index)
  - [Paradigms](#paradigms)
    - [ASSR](#assr)
    - [ASSR oddball](#assr-oddball)
    - [AVSRT](#avsrt)
    - [Beep-flash sfari](#beep-flash-sfari)
    - [Cued Boss - inhibition](#cued-boss)
    - [F.A.S.T. Response task](#f-a-s-t--response-task)
    - [Flanker task](#flanker-task)
    - [Illusory Contours](#illusory-contours)
    - [N-Back task](#n-back-task)
    - [Oddball experiments](#oddball-experiments)
    - [Restingstate with Eyetracking](#restingstate-with-eyetracking)
    - [Swat](#swat)
    - [Visual working memory task](#visual-working-memory-task)
  - [Pipelines](#pipelines)
    - [Anticipatory activity in ASD](#anticipatory-activity-in-ASD)
    - [Pipeline EEG to ERP EEGlab stats R](#pipeline-eeg-to-erp-eeglab-stats-r)
    - [Resting state Pipeline- Pre-process/Microstates/PowerFrequency](#resting-state-pipeline--pre-processmicrostatespowerfrequency)
    - [Sfari pipelines all paradigms](#sfari-pipelines-all-paradigms)
    - [Speech-in-noise pipeline](#speech-in-noise-pipeline)
    - [Test-retest](#test-retest)
  - [Statistics](#statistics)
    - [FDR (false discovery rate)](#fdr-false-discovery-rate)
    - [Mixed effect models](#mixed-effect-models)
    - [Rett Standard ITPC](#rett-standard-itpc)
  - [Toolboxes](#toolboxes)
    - [EEGlab](#eeglab)
    - [Fieldtrip](#fieldtrip)
    - [LIMO Tools](#limo-tools)
    - [mTRF-Toolbox](#mtrf-toolbox)
  - [Utilities](#utilities)
    - [Adding Eyelink to a Presentation® Experiment](#adding-eyelink-to-a-presentation-experiment)
    - [Practicing deleting components after ICA](#practicing-deleting-components-after-ica)
    - [readme template](#readme-template)
    - [Trial by trial data export eeglab](#trial-by-trial-data-export-eeglab)
    - [Using interpolation to go from 160 channel data to 64](#using-interpolation-to-go-from-160-channel-data-to-64)
  - [Working Repos](#working-repos)
    - [PPE Mobile](#ppe-mobile)
                                         
      


<!-- ABOUT THE PROJECT -->
## How to keep this index up-to-date
To find all the code we put online, we need some sort of overview. We have this by looking at this index. However this index only works if we all keep it up-to-date together. Plus once you make a change, you will be part of the contributors, so people can see that you worked on this. Showing that we do this all together.

### Who should add to this index
Anyone that adds a repo to the CNL page. It doesn't matter if you created it or if you only forked it. If you put it in the main CNL GitHub, you need to add to this index. If you do not do this, it might get deleted after a while to prevent us loosing track of what is what.

### When to add to this index
As soon as you add anything to the main CNL GitHub.

### How to add to this index
#### create a new Repo branch
create a new branch by clicking on the "main button" and typing a name for your new branch and clicking the create branch option. 
![opening a new branch](https://github.com/CognitiveNeuroLab/Index_overview_CNL/blob/main/image/new%20branch.PNG "new branch")

#### Adding a new sub-group
Let's say you are the first to create the subgroup "pipelines". You look below the line that says "## index" and look alphabetically where it goes. Since it's a subgroup, you put 2 # before the name + 1 space. 
After that you need to add this also to the table of content. You do this by scrolling up to the table of content, look where your subgroup goes and add it there by writing the title as is in between [] directly followed by the title without capitals and spaces/underscores replaced by - in-between ().
Make sure there is the same amount of indents as for the other sub-groups.
#### adding a Repo
Find the right subgroup and lets say in this case you want to upload your pipeline. Look for "### pipelines", and see where your pipeline goes alphabetically. add 4 # before the name of your repo. Then enter the name of your repo between []followed by the URL inside (). 
In the line below write a quick explanation with at least the following info, year when uploaded, who created the Fork, what language you used, references if they exist. You can add more, but try to keep it as short as possible, since every repo should have a readme that explains itself. 
After that you need to add this also to the table of content. You do this by scrolling up to the table of content, look for your subgroup and add it below there (alphabetically) by writing the title as is in between [] directly followed by the title without capitals and spaces/underscores replaced by - in-between ().
Make sure there is the same amount of indents as for the other repos.
#### combining the new and the original branch
After saving all the changes you made in the new branch. Click on the "pull requests button". Click the green "New pull request" button. Make sure you are comparing the right branches with each other. This means the "main" branch should be the first box and whatever you called yours should be in the one on the right. After that you hit "create pull request" two times. If correct you can now choose "merge pull request". After this you should delete your old branch.

## Index
The index is divided in sub-groups. If your repo does not fall within a subgroup, feel free to create a new one.

### Paradigms  
#### [ASSR](https://github.com/CognitiveNeuroLab/ASSR)
2018 - Olga Sysoeva - Presentation paradigm - - created and used for Olga and Tufikameni's Rett project
#### [ASSR Oddball](https://github.com/CognitiveNeuroLab/ASSR-oddball)
2022 - Douwe Horsthuis - presentation paradigm - created and used for SFARI project (2021)  
#### [AVSRT](https://github.com/CognitiveNeuroLab/avsrt)  
???? - Lab Paradigm - Presentation paradigm - published on mulitple times  
#### [Beep-Flash SFARI](https://github.com/CognitiveNeuroLab/beep-flash-sfari)
2014 - Lab Paradigm - Presentation paradigm - Adaptation of Beep-flash-kids (2014) Used orignally for [Murphy paper](https://onlinelibrary.wiley.com/doi/full/10.1002/aur.1374)  
#### [Cued boss](https://github.com/CognitiveNeuroLab/Experiment_Cued_BOSS_Active_and_passive_inhibition)
2020 - Douwe Horsthuis - Presentation paradigm - created and used for Ana Francisco's 22q and schizophrenia research to measure active and passive inhibition.  
#### [F.A.S.T. Response task](https://github.com/CognitiveNeuroLab/F.A.S.T.-response-experiment)
2022 - Douwe Horsthuis - Presentation Paradigm - created and used for SFARI project (2021)
#### [Flanker task](https://github.com/CognitiveNeuroLab/Flanker_task_experiment)
2021 - Douwe Horsthuis - Presentation paradigm - created and used for Ana Francisco's cystinosis project (2021)  
#### [Illusory Contours](https://github.com/CognitiveNeuroLab/Illusory-Contours)
2021 - Emily Knight - Presentation paradigm - creatd and used for specific ASD study, modified for Sfari project
#### [N-Back task](https://github.com/CognitiveNeuroLab/N-back-task-experiment)
2021 - Douwe Horsthuis - Presentation Paradigm - Created and used for Ana Francisco's Cystinosis Project (2021)
#### [Oddball experiments](https://github.com/CognitiveNeuroLab/Oddball_experiments)
2021 - Douwe Horsthuis - Presentation Paradigm - visual Duration discrimination - created and used for Ana Francisco's cystinosis project  (2021)  
2021 - Douwe Horsthuis - Presentation Paradigm - Visual Oddball - created but not used for Ana Francisco's cystinosis project (2021)  
2021 - Luke Shaw - presentation Paradigm - Oddball duration tone - created and used for several lab studies - updated with extra soas by Douwe  
2020 - Douwe Horsthuis - Presentation Paradigm - Duration discrimination - created and used for Ana Francisco's 22q/schizophrenia cystinosis project  (2021)   
2020 - Douwe Horsthuis - Presentation Paradigm - Omission - created and used for Ana Francisco's 22q/schizophrenia project  (2020)     
2020 - Douwe Horsthuis - Presentation Paradigm - Rhythm - created and used for Ana Francisco's 22q/schizophrenia (2021)  
#### [Restingstate with eyetracking](https://github.com/CognitiveNeuroLab/restingstate-with-eyetracking)
2022 - Douwe Horsthuis - Presentation Paradigm - Simple restingstate paradigm with eyetracking for SFARI project (2021)
#### [swat](https://github.com/CognitiveNeuroLab/swat-experiment)  
2021 - Douwe Horsthuis - Presentation Paradigm - updated the swat_kids paradigm (2021) 
original used for [Wylie Javitt Foxe](https://www.sciencedirect.com/science/article/pii/S1053811903005044)
#### [Visual working memory task](https://github.com/CognitiveNeuroLab/Visual_working_memory_experiment)
2021- Douwe Horsthuis - Presentation paradigm - created for Ana Francisco's Cystinosis project (2021)

### Pipelines
#### [Anticipatory activity in ASD](https://github.com/Shlomit-Beker/Anticipatory-activity-in-ASD)
  2021 - Shlomit Beker - Matlab - Anticipatory analysis of data from ASD children (aka VAMP)
  
    - Beker, S., Foxe, J. J., Molholm S., (https://www.biorxiv.org/content/10.1101/2020.05.07.083154v1)
#### [Pipeline EEG to ERP EEGlab stats R](https://github.com/DouweHorsthuis/EEG_to_ERP_pipeline_stats_R)
2021 - Douwe Horsthuis - Matlab and R - EEG pipeline relying on EEGlab/ERPlab and potential for statistics (including mixed effect models) in R studio

    - Francisco, A. A., Foxe, J. J., Horsthuis, D. J., DeMaio, D., & Molholm, S. (2020). Assessing auditory processing endophenotypes associated with Schizophrenia in individuals with 22q11. 2 deletion syndrome. Translational psychiatry, 10(1), 1-11
    - Francisco, A. A., Horsthuis, D. J., Popiel, M., Foxe, J. J., & Molholm, S. (2020). Atypical response inhibition and error processing in 22q11. 2 Deletion Syndrome and schizophrenia: Towards neuromarkers of disease progression and risk. NeuroImage: Clinical, 27, 102351.
    - Francisco, A. A., Foxe, J. J., Horsthuis, D. J., & Molholm, S. (2020). Impaired auditory sensory memory in Cystinosis despite typical sensory processing: A high-density electrical mapping study of the mismatch negativity (MMN). NeuroImage: Clinical, 25, 102170.
    - Francisco, A. A., Berruti, A. S., Kaskel, F. J., Foxe, J. J., & Molholm, S. (2021). Assessing the integrity of auditory processing and sensory memory in adults with cystinosis (CTNS gene mutations). Orphanet Journal of Rare Diseases, 16(1), 1-10.  
#### [Resting state Pipeline- Pre-process/Microstates/PowerFrequency](https://github.com/CognitiveNeuroLab/resting-state-analysis-pipeline-microstates-frequency)  
2021 - Ana Francisco, Douwe Horsthuis, Filip De Sanctis - Matlab - Pipeline to analyse Resting state data using EEGlab, looking at microstates and power/frequency
#### [Sfari pipelines all paradigms](https://github.com/CognitiveNeuroLab/sfari-analysis-pipelines)  
2022 - Douwe Horsthuis, Shlomit Beker, Filip De Sanctis, Sophie Molholm - Pipeline to analyse all Sfari projects, mostly frequency domain related  
#### [Speech-in-noise pipeline](https://github.com/CognitiveNeuroLab/Speech-in-noise-pipeline)
2021 - General lab effort - Matlab SPSS - Pipeline to pre-process SiN data
#### [Test-retest](https://github.com/Shlomit-Beker/Test-retest)
2021 - Shlomit Beker - Matlab - Test-retest 
  
      - Beker, S. Foxe, J.J., Venticinque, J. et al., Journal of Neurodevelopmental Disorders (2021)  
 

### Statistics
#### [FDR (false discovery rate)](https://github.com/Shlomit-Beker/FDR)
2021- Shlomit Beker - Matlab - FDR (false discovery rate)  
#### [Mixed effect models](https://github.com/anafrancisco/Mixed-effect-models)
2021- Ana Francisco - R - Mixed effect models - Single trial data. 
#### [Rett Standard ITPC](https://github.com/Shlomit-Beker/Rett_standard_ITPC)
2021- Shlomit Beker - Matlab - Rett Standard ITPC

### Toolboxes
#### [EEGlab](https://github.com/CognitiveNeuroLab/eeglab)
2021 - (forked) SCCN/UCSD - Matlab - EEGLAB is an open source signal processing environment for electrophysiological signals running on Matlab and developed at the SCCN/UCSD
#### [Fieldtrip](https://github.com/CognitiveNeuroLab/fieldtrip)
2021- (forked) Donders institute -Matlab - The MATLAB toolbox for MEG, EEG and iEEG analysis
#### [LIMO tools](https://github.com/CognitiveNeuroLab/limo_tools)
2019- (forked)  LIMO Team - Hierarchical Linear Modelling for MEEG data
#### [mTRF-Toolbox](https://github.com/CognitiveNeuroLab/mTRF-Toolbox)
2020- (forked) Mick cross - Matlab - A MATLAB Package for Relating Neural Signals to Continuous Stimuli

### Utilities
#### [Adding Eyelink to a Presentation® Experiment](https://github.com/CognitiveNeuroLab/Adding-Eyelink-to-experiment)
2021 - Douwe Horsthuis - Presentation - Presentation code that is needed to add eye tracking to your paradigm, double checked by the people from [SR-research](https://www.sr-research.com/). 
#### [Practicing deleting components after ICA](https://github.com/CognitiveNeuroLab/ICA_Practice)
2021 - Ana Francisco, Douwe Horsthuis, Filip De Sanctis, Sophie Molholm and Seyda Tikir - Matlab - A script for practicing what components to delete after doing ICA using EEGlab and its IClabel toolbox to verify.
#### [Using interpolation to go from 160 channel data to 64](https://github.com/CognitiveNeuroLab/Interpolating_160ch_to_64ch_eeglab)
2021 - Douwe Horsthuis - Matlab - function that transforms your 160 channel data into 64, leaving the landmark channels alone. 
#### [Readme Template](https://github.com/CognitiveNeuroLab/README-Template)
2019 - (forked)othneildrew - HTML/Markdown - Readme template for Github
#### [Trial by trial data export eeglab](https://github.com/CognitiveNeuroLab/trial_by_trial_data_export_eeglab)
2021 - Douwe Horsthuis - Matlab - to export data from EEGlab to external programs keeping individual trials.  
  
  
### Working Repos
These repos are currently in use to work in colaboration on projects. Most will be set to private. This means that you cannot google them, you cannot see/find them unless you are a part of this github organization. 
  
#### [PPE Mobile](https://github.com/CognitiveNeuroLab/ppe-mobile)



## License

Distributed under the MIT License. See `LICENSE` for more information.


## Contact

Cognitive Neurophysiology Lab - [@CNL_Einstein](https://twitter.com/CNL_Einstein) - cnl@einsteinmed.org - cogneurolabrochester@gmail.com  
https://www.cognitiveneurolab.com/
https://www.urmc.rochester.edu/labs/cognitive-neurophysiology.aspx  



[contributors-shield]: https://img.shields.io/github/contributors/CognitiveNeuroLab/Index_overview_CNL.svg?style=for-the-badge
[contributors-url]: https://github.com/CognitiveNeuroLab/Index_overview_CNL/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CognitiveNeuroLab/Index_overview_CNL.svg?style=for-the-badge
[forks-url]: https://github.com/CognitiveNeuroLab/Index_overview_CNL/network/members
[stars-shield]: https://img.shields.io/github/stars/CognitiveNeuroLab/Index_overview_CNL.svg?style=for-the-badge
[stars-url]: https://github.com/CognitiveNeuroLab/Index_overview_CNL/stargazers
[issues-shield]: https://img.shields.io/github/issues/CognitiveNeuroLab/Index_overview_CNL.svg?style=for-the-badge
[issues-url]: https://github.com/CognitiveNeuroLab/Index_overview_CNL/issues
[license-shield]: https://img.shields.io/github/license/CognitiveNeuroLab/Index_overview_CNL.svg?style=for-the-badge
[license-url]: https://github.com/CognitiveNeuroLab/Index_overview_CNL/blob/master/LICENSE.txt


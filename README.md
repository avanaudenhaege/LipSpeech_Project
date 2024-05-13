# LipSpeech_project

Code for stimulation used in the localizer and MVPA experiments (fMRI design)

Alice Van Audenhaege - May 2024

## Install

There are some git submodules needed to run the code. 
To clone the repository and all submodules, use the following command:

```
git clone -- recursive https://github.com/avanaudenhaege/LipSpeech_project.git
```

## Description

This repository contains scripts for 4 experiments : 
1. PhonologicalDecoding_MVPA : 
- event-related experiment
- during which syllables are presented in separated auditory and visual runs

2. VOTC_localizer : 
- block-design experiment
- functional localization of VWFA, FFA and PPA regions in VOTC
- during which images of houses, faces and words are presented

3. AuditorySpeech_localizer :
- block-design experiment
- functional localization of auditory speech-selective regions (voice and phonology)
- during which audio clips of speech and scrambled speech are presented

4. AuditorySpeech_localizer :
- block-design experiment
- functional localization of visual speech-selective regions (lipreading and non-linguistic lip movements)
- during which videos of visual speech and non-linguistic lipmovements are presented


### Stimuli

All stimuli used in the experiments are available on OSF in their related folder : 

https://osf.io/2xtsn/?view_only=22f09bb4dc5f4a11823103141ca2f735

To download them just type (for MacOS and linux):

```bash
make clean
make stimuli
```

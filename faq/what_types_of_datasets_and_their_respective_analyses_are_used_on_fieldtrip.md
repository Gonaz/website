---
title: Which datasets are used in the documentation and where are they used?
tags: [faq, tutorial, dataset]
---

# Which datasets are used in the documentation and where are they used?

The FieldTrip website and ftp server include a variety of datasets. some of these are used in the [tutorials](/tutorial), while others are used in [example MATLAB scripts](/example). All of these datasets were recorded from humans, unless otherwise specified.

In this [frequently asked question](/faq/open_data) you can find links to other open access datasets.

## MEG-language

* Dutch sentences presented auditorily. Investigated the effects of semantic congruency and incongruency on sentence processing.
* 151-channel CTF Omega System
* Anatomical MRI scan of Subject01 from this dataset is included and used for the headmodel tutorials
* Details [MEG-language](/tutorial/meg_language)
* Link to [publication](http://dx.doi.org/10.1002/hbm.21410) by Wang et al.(2011)
* Download the dataset[Subject01.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/Subject01.zip) from our FTP server.
* There are some additional single-subject raw datasets from this study, which were in the past used to show the effect of the planar gradient transform but which are not used at the moment. These are available from our FTP server as Subject02.zip, Subject03.zip and Subject04.zip. These additional subjects are also used to explain batch processing and distributed computing.
* Group results of this study (comprising 10 subjects) are used in the statistics tutorials.

Tutorials using this dataset:
{% include seealso tag1="meg-language" %}

## MEG-artifact

* Dataset specifically generated by FieldTrip members for teaching artifact rejection.
* Data composed of 10s segments with no gaps between segments.
* Download the dataset[ArtifactMEG.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/ArtifactMEG.zip) from our FTP server.

Tutorials using this dataset:
{% include seealso tag1="meg-artifact" %}

## MEG-visuomotor151

* Right wrist is maintained in isometric extension against a lever until visual stimulus changes speed. Modulation of the hazard rate of the stimulus' speed change: UP-schedule (likelihood of stimulus change *increases* as the duration of the constant stimulus increases) and DOWN-schedule (likelihood of stimulus to change *decreases* a duration of the constant stimulus increases). Analysed change in coherence between oscillations in motor cortex and spinal cord neurons as an indicator of corticospinal interaction.

* 151 CTF System + Electromyography (EMG) recording
* Link to the [publication](http://dx.doi.org/10.1126/science.1107027) by Schoffelen et al.(2005)
* Download the dataset [subjectK.mat](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/sensor_analysis/subjectK.mat) from our FTP server.

Tutorials using this dataset:
{% include seealso tag1="meg-visuomotor151" %}

## MEG-visuomotor151_02

* Both wrists in isometric extensions to exert a constant force against a lever. Indicate detected change (speed) of visual stimulus by further extending cued hand. Analyzed the gamma-band coherence as an indicator of communication between sensorimotor regions and and motorneurons in the forearm.
* 151 CTF MEG system
* Download the [publication](http://dx.doi.org/10.1523/JNEUROSCI.4882-10.2011) by Schoffelen et al.(2011).
* Download the dataset [SubjectCMC.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/SubjectCMC.zip) from our FTP server.

Tutorials using this dataset:
{% include seealso tag1="meg-visuomotor275" %}

## MEG-attention

* Covertly attend to cued square: left or right (hemifield). Used alpha oscillations in covert attention as a classifier (left vs. right) for use in brain computer interface.
* 275 CTF MEG system
* Download the dataset [covatt.mat](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/classification/covatt.mat) from our FTP server.
* Link to the [publication](http://dx.doi.org/10.1016/j.neunet.2009.06.004) by van Gerven et al.(2009).

Tutorials using this dataset:
{% include seealso tag1="meg-attention" %}

## MEG-tactile

* Dataset specifically generated by FieldTrip team members to explain dipole-fitting
* Different forms of mechanical tactile stimulation applied to right index finger.
* Download the dataset[TactileStimulusDipolefit.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/TactileStimulusDipolefit.zip) from our FTP server.

Tutorials using this dataset:
{% include seealso tag1="meg-tactile" %}

## MEG-audodd

* Combined MEG/EEG dataset recorded at the NatMEG on the Elekta Triux MEG scanner
* Aditory stimulus presentation with a standard and an oddball, motor responses on the oddball, response hand was cued left or right at the start of each block
* Dataset [details](/tutorial/natmeg/meg_audodd)
* Download the dataset[ftp:/ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/natmeg](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/natmeg)

Tutorials using this dataset:
{% include seealso tag1="meg-audodd" %}

## EEG-language

* Dutch words presented in visual form, auditory form, and picture form. Multivariate pattern analysis used to decode conceptual representations from event-related data
* 64 channel ActiCap system (Brain Products GmbH)
* Link to [publication](http://dx.plos.org/10.1371/journal.pone.0014465) by Simanova et al.(2010).
* Download the dataset [SubjectEEG.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/SubjectEEG.zip) from our FTP server

Tutorials using this dataset:
{% include seealso tag1="eeg-language" %}

## EEG-affective

* Dutch words presented in visual form, subjects made positive/negative or animal/human judgments on the nouns.
* 64 channel ActiCap system (Brain Products GmbH)
* Download the dataset [here](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/preprocessing_eeg) from our FTP server

Tutorials using this dataset:
{% include seealso tag1="eeg-affective" %}

## EEG-TMS

* Data specifically generated by FieldTrip team members for teaching TMS/EEG data analysis.
* Transcranial magnetic stimulation applied to primary motor cortex (M1) while subject contracts or relaxes contralateral hand.
* C-B60 butterfly coil connected to a MagPro X100 (Magventure) stimulator &  61 channel TMS-compatible EEG cap (EasyCap)
* Download the dataset [sp_motor.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/tms/sp/sp_motor.zip) from our FTP server.

Tutorials using this dataset:
{% include seealso tag1="eeg-tms" %}

## HCP-motort

* Motor task dataset from HCP project
* Recorded at 2000Hz with 248-channel 4D/BTi MEG scanner in St. Louis, USA.
* Subjects do a movement of left hand, right hand, left foot or right foot.
* Details [HCP-motort](/tutorial/hcp_motort)
* Download the dataset from the [HCP website](http://db.humanconnectome.org).

Tutorials using this dataset:
{% include seealso tag1="hcp-motort" %}

## mmfaces

* EEG, MEG, fMRI and structural MRI data from 16 subjects, also used in SPM8 and SPM12 documentation
* Recorded by Rik Hanson and colleagues in Cambridge, using 306-channel Elekta/Neuromag system
* Subjects watch familiar, unfamiliar and scrambled faces
* Download the dataset from the [MRC-CBU](ftp://ftp.mrc-cbu.cam.ac.uk/personal/rik.henson/wakemandg_hensonrn) FTP server.
* Details [mmfaces](/tutorial/mmfaces)

Tutorials using this dataset:
{% include seealso tag1="mmfaces" %}

## MEG-epilepsy

* This dataset contains MEG data from two patients. The data was recorded at Aston Brain Centre (ABC) using a 275-channel CTF system and using an Elekta 306-channel system, i.e. for both patients there are the recordings with the two MEG systems. This clinical data was kindly provided by Professor Stefano Seri.
* The data is available from ftp:/ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/epilepsy

Tutorials using this dataset:
{% include seealso tag1="meg-epilepsy" %}

## Spike-attention

* Monkeys attended to relevant the stimulus while ignoring distracters. Analysed activity in V4 as a function of whether neurons were activated by stimulus or distracters
* Link to the [publication](http://dx.doi.org/10.1126/science.1055465) by Fries et al.(2001).
* Download the dataset[p029_sort_final_01.nex.](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/spikefield/p029_sort_final_01.nex.) from our FTP server.

Tutorials using this dataset:
{% include seealso tag1="spike-attention" %}

## Spike-placefield

* Rat CA1 hippocampal activity measured as rat explores maze
* Download the dataset [tt6_7.t](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/spike/tt6_7.t) from our FTP server.

Tutorials using this dataset:
{% include seealso tag1="spike-placefield" %}

## ECoG-visual

* ECoG data recorded at the Comprehensive Epilepsy Center of the New York University School of Medicine and processed in collaboration with members of the Multisensory Integration Research Group (Charité - University Medicine Berlin).
* The data was recorded from an epilepsy patient implanted with a subdural grid for pre-surgical evaluation and includes a visual localizer task. different types of visual stimuli were presented.
* Download the dataset [SubjectNY394.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/SubjectNY394.zip)

Tutorials using this dataset:
{% include seealso tag1="ecog-visual" %}

## ECoG-protocol

* Intracranial EEG data (ECoG and Stereo EEG) obtained at the UC Irvine Medical Center. Includes a pre-implantation MR and a post-implantation CT, the latter showing the recording electrodes.
* Download the dataset [SubjectUCI29.zip](ftp://ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/SubjectUCI29.zip)

Tutorials using this dataset:
{% include seealso tag1="ecog-protocol" %}

## NIRS single channel

* Single-channel fNIRS recording of motorcortex using an Oxymon MK III system of Artinis Medical Systems during finger tapping task.
* Download the data here ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/nirs_singlechannel/motor_cortex.oxy3

Tutorials using this dataset:
{% include seealso tag1="nirs-singlechannel" %}

## NIRS multi channel

* Download the dataset here ftp.fieldtriptoolbox.org/pub/fieldtrip/tutorial/nirs_multichannel
* The fNIRS data was recorded using 4 connected Oxymon systems from Artinis to enable a 48 channel recording. Data was sampled at 250 Hz. Data was recorded during an event-related auditory oddball paradigm.

Tutorials using this dataset:
{% include seealso tag1="nirs-multichannel" %}

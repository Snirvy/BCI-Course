
## ChatGPT summary
The paper by Nicolas-Alonso & Gomez-Gil, 2012 is a review of Brain-Computer Interface (BCI) systems. The authors provide an overview of the history of BCI technology and its development, including the different types of BCIs, the physiological basis of BCI, and its current state of the art. They discuss the challenges and limitations of BCI systems, such as the need for individualized calibration and the limited number of degrees of freedom. The authors also outline the future directions for BCI research and development, including the integration of BCIs with other assistive technologies, the development of more natural and intuitive BCI interfaces, and the use of BCIs for rehabilitation and therapy.


## Abstract
A brain-computer interface (BCI) is a hardware and software communications  
system that permits cerebral activity alone to control computers or external devices. The  
immediate goal of BCI research is to provide communications capabilities to severely  
disabled people who are totally paralyzed or ‘locked in’ by neurological neuromuscular  
disorders, such as amyotrophic lateral sclerosis, brain stem stroke, or spinal cord injury.  
Here, we review the state-of-the-art of BCIs, looking at the different steps that form a  
standard BCI: signal acquisition, preprocessing or signal enhancement, feature extraction,  
classification and the control interface. We discuss their advantages, drawbacks, and latest  
advances, and we survey the numerous technologies reported in the scientific literature to  
design each step of a BCI. First, the review examines the neuroimaging modalities used in  
the signal acquisition step, each of which monitors a different functional brain activity such  
as electrical, magnetic or metabolic activity. Second, the review discusses different  
electrophysiological control signals that determine user intentions, which can be detected  
in brain activity. Third, the review includes some techniques used in the signal enhancement  
step to deal with the artifacts in the control signals and improve the performance. Fourth,  
the review studies some mathematic algorithms used in the feature extraction and  
classification steps which translate the information in the control signals into commands  
that operate a computer or other device. Finally, the review provides an overview of  
various BCI applications that control a range of devices.

## Introduction
- Distortions from eye & muscle movements

### EEG
- Cheap
- Temporal good
- Non invasive


### MEG
- Magnetic based imaging
- Need superconductor
- Also magnet proof room

### ECOG
- Implant, invasive
- Long term stability unknown
- Biological acceptance/rejection
- Potential of damaging subject
- Overtime degradation of signal

### fMRI
- Blood oxygen levels
- Bulky equipment

### fNIRS
- Shallow
- Lightweight & cheap


## Paradigms

### Exogenous vs Endogenous

### Synchronous vs Asynchronous

## Analysis and processing

### SSA
stationary subspace analysis (SSA) has recently been introduced to deal with the  
non-stationarity of EEG signals [154]. SSA decomposes multivariate time series into stationary and  
non- stationary components.


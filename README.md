# Using electrodermal activity to detect deception and suspicion during a card game

In this project I focus on detection of deception and suspicion from
electrodermal activity (EDA) measured on left and right wrists during a dyadic game interaction. I aim to answer three research
questions: 

*  (i) Is it possible to reliably distinguish deception from truth based on EDA measurements during a dyadic game interaction? <br>
*	(ii) Is it possible to reliably distinguish the state of suspicion from trust based on EDA measurements during a card game? <br>
*	(iii) What is the relative importance of EDA measured on left and right wrists? <br>

To answer my research questions I conducted a study in which 20 participants were playing the game Cheat in pairs with 
one EDA sensor placed on each of their wrists. My experimental results show that EDA measures from left and right
wrists provide more information for suspicion detection than for
deception detection and that the person-dependent detection is
more reliable than the person-independent detection. In particular,
classifying the EDA signal with Support Vector Machine (SVM)
yields accuracies of 52% and 57% for person-independent prediction of deception and suspicion respectively, and 63% and 76% for
person-dependent prediction of deception and suspicion respectively. Also, I found that: 

*	(i) the optimal interval of informative EDA signal for deception detection is about 1 s while it is around 3.5 s for suspicion detection; <br>
*	(ii) the EDA signal relevant for deception/suspicion detection can be captured after around 3.0 seconds
after a stimulus occurrence regardless of the stimulus type (deception/truthfulness/suspicion/trust); and that 
*	(iii) features extracted from EDA from both wrists are important for classification of both
deception and suspicion. <br>To the best of my knowledge, this is the
first work that uses EDA data to automatically detect both deception
and suspicion in a dyadic game interaction setting.

This project resulted in the following **conference paper**:

Jan Ondras and Hatice Gunes.<br>
[*Detecting Deception and Suspicion in Dyadic Game Interactions.*](https://dl.acm.org/citation.cfm?id=3242993)<br>
In 20th ACM International Conference on Multimodal Interaction (ACM ICMI), 2018.<br>
*Oral presentation.*

### Citation

	@inproceedings{Ondras2018DetectingDA,
	  title={Detecting Deception and Suspicion in Dyadic Game Interactions},
	  author={Jan Ondras and Hatice Gunes},
	  booktitle={ICMI '18},
	  year={2018}
	}

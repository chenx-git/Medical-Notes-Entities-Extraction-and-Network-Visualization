# Medical-notes-entities-extraction-and-network-visualization
Using ScispaCy to extract and identify entities in medical texts and generate networks visualizations
### Data Source---https://www.kaggle.com/c/medical-notes/data
### NLP package used: ScispaCy---https://www.semanticscholar.org/paper/ScispaCy%3A-Fast-and-Robust-Models-for-Biomedical-Neumann-King/de28ec1d7bd38c8fc4e8ac59b6133800818b4e29
### Data format--text
### exmaple:
B>STUDY:  </B>A trial of Passy-Muir valve was completed to allow the patient to achieve hands-free voicing and also to improve his secretion management.  A clinical swallow evaluation was not completed due to the severity of the patient's mucus and lack of saliva control.

The patient's laryngeal area was palpated during a dry swallow and he does have significantly reduced laryngeal elevation and radiation fibrosis.  The further evaluate of his swallowing function is safety; a modified barium swallow study needs to be concluded to objectively evaluate his swallow safety, and to rule out aspiration.  A trial of neuromuscular electrical stimulation therapy was completed to determine if this therapy protocol will be beneficial and improving the patient's swallowing function and safety.

For his neuromuscular electrical stimulation therapy, the type was BMR with a single mode cycle time is 4 seconds and 12 seconds off with frequency was 60 __________ with a ramp of 2 seconds, phase duration was 220 with an output of 99 milliamps.  Electrodes were placed on the suprahyoid/submandibular triangle with an upright body position, trial length was 10 minutes.  On a pain scale, the patient reported no pain with the electrical stimulation therapy.

<B>FINDINGS:  </B>The patient was able to tolerate a 5-minute placement of the Passy-Muir valve.  He reported no discomfort on the inhalation; however, he felt some resistance on exhalation.  Instructions were given on care placement and cleaning of the Passy-Muir valve.  The patient was instructed to buildup tolerance over the next several days of his Passy-Muir valve and to remove the valve at anytime or he is going to be sleeping or napping throughout the day.  The patient's voicing did improve with the Passy-Muir valve due to decreased leakage from his trach secondary to finger occlusion.  Mucus production also seemed to decrease when the Passy-Muir was placed.

On the dry swallow during this evaluation, the patient's laryngeal area is reduced and tissues around his larynx and showed radiation fibrosis.  The patient's neck range of motion appears to be adequate and within normal limits.

## 2 jupyter notebook
<li> from medical note text data, extract entities informaiton to edges and nodes dataframe and stored in csv
<li> build network and sub-networks to visualize the entities relationship

## Some network graphs:
![overall network](https://github.com/eduhkdcx/Medical-notes-entities-extraction-and-network-visualization/blob/main/plots/whole.png)
![abd sub network](https://github.com/eduhkdcx/Medical-notes-entities-extraction-and-network-visualization/blob/main/plots/abd.png)
![duo sub network](https://github.com/eduhkdcx/Medical-notes-entities-extraction-and-network-visualization/blob/main/plots/duo.png)

# Medical-Notes-Entities-Extraction-and-Network-Generation
Using ScispaCy to extract and identify entities in medical texts and generate networks visualizations
## <li>Data Source---https://www.kaggle.com/c/medical-notes/data
### NLP package used--ScispaCy <br>Website: https://spacy.io/universe/project/scispacy
## <li>Data format--text
### Text Data Example:
> B>STUDY:  </B>A trial of Passy-Muir valve was completed to allow the patient to achieve hands-free voicing and also to improve his secretion management.  A clinical swallow evaluation was not completed due to the severity of the patient's mucus and lack of saliva control.

> The patient's laryngeal area was palpated during a dry swallow and he does have significantly reduced laryngeal elevation and radiation fibrosis.  The further evaluate of his swallowing function is safety; a modified barium swallow study needs to be concluded to objectively evaluate his swallow safety, and to rule out aspiration.  A trial of neuromuscular electrical stimulation therapy was completed to determine if this therapy protocol will be beneficial and improving the patient's swallowing function and safety.

> For his neuromuscular electrical stimulation therapy, the type was BMR with a single mode cycle time is 4 seconds and 12 seconds off with frequency was 60 __________ with a ramp of 2 seconds, phase duration was 220 with an output of 99 milliamps.  Electrodes were placed on the suprahyoid/submandibular triangle with an upright body position, trial length was 10 minutes.  On a pain scale, the patient reported no pain with the electrical stimulation therapy.


## <li>Project Consists of: 2 jupyter notebook files
### 1. **NLP**: from medical note text data, extract entities informaiton to edges and nodes dataframe and stored in csv --- ScispaCy 
### 2. **Network Visualization**: build network and sub-networks to visualize the entities relationship --- NetworkX


## Some network graphs:
![overall network](https://github.com/eduhkdcx/Medical-notes-entities-extraction-and-network-visualization/blob/main/plots/whole.png)
![abd sub network](https://github.com/eduhkdcx/Medical-notes-entities-extraction-and-network-visualization/blob/main/plots/abd.png)
![duo sub network](https://github.com/eduhkdcx/Medical-notes-entities-extraction-and-network-visualization/blob/main/plots/duo.png)

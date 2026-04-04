# Dysenet based dysarthric severity classifier
The classification of dysarthric severity was conducted in two stages. Initially, psycho-acoustic features were extracted from the speech signal. Subsequently, the acoustic feature representation was utilized to determine dysarthric severity at the segment level.
## Acoustic feature representation
The psycho-acoustic feature representation was obtained from Mel-frequency cepstral coefficient and bark band energies.
## Dysenet architecture
The psyco-acoustic features and its labels are fed to the dysenet classifier to predict the severity at the frame level. The dysenet layers are shown below

## Results
The proposed dysenet classifier predicts the severity at the frame level. This research helps the speech language pathologies to analyse the severity at the frame level. Further, the analysis can be extended to phoneme-level as shown in figure
![Dysenet severity classfication at phoneme-level for analysis](https://github.com/Minipriya-Ravi/Dysenet/blob/main/dysenet_sev_utt.png)


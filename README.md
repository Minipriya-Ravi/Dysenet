# Dysenet based dysarthric severity classifier
The classification of dysarthric severity was conducted in two stages. Initially, psychoacoustic features were extracted from the speech signal. Subsequently, the acoustic feature representation was utilized to determine dysarthric severity at the segment level.
## Acoustic feature representation
The psychoacoustic feature representation was obtained from the Mel-frequency cepstral coefficient and bark band energies.
## Dysenet architecture
The psychoacoustic features and their labels are fed to the dysenet classifier to predict the severity at the frame level. The dysenet layers are shown below

![Dysenet architecture](/dysenet-architecture.png)

The working code was mentioned in the notebook [file](/Dysenet.ipynb) 

## Results
The proposed dysenet classifier predicts the severity at the frame level. This research helps the speech language pathologist to analyse the severity at the frame level. Further, the analysis can be extended to the phoneme level as shown in the figure.
![Dysenet severity classfication at phoneme-level for analysis](https://github.com/Minipriya-Ravi/Dysenet/blob/main/dysenet_sev_utt.png)

## Citation
please cite our work:
```bibtex
@article{dysenet2026,
  title={Dysenet: A segment level severity classification approach for identifying sound-specific speech challenges in dysarthric speech},
  author={Minipriya R and Poonkuzhali S},
  journal={submitted for consideration in International Journal of Speech-Language Pathology },
  year={2026}
}

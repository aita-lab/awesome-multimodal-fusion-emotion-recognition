# <p align=center>`Multi-Modal Fusion in Speech Emotion Recognition: A Comprehensive Review of Methods and Technologies`</p> #

### Citation
```python
# Update soon
```
### Update
- **First release:** December 3rd, *2024*. 

## Contents
- [Related Survey](#related-survey)
- [Data sets](#data-sets)
- [Review of fusion methods in SER](#review-of-fusion-methods-in-ser)
    - [Early fusion](#early-fusion)
    - [Late fusion](#late-fusion)
    - [Deep-fusion](#deep-fusion)
    - [Hybrid-fusion](#hybrid-fusion)
- [Review of fusion technologies in SER](#review-of-fusion-technologies-in-SER)
    - [Data representation](#data-representation)
    - [Data translation](#data-translation)
    - [Attention mechanism](#attention-mechanism)
        - [Multi-head attention](#multi-head-attention)
        - [Cross-modality attention](#cross-modality-attention)
        - [Dual-attention network](#dual-attention-network)
        - [Graph attention network](#graph-attention-network)
    - [Graph-based fusion](#graph-based-fusion)


## Related Survey
**A snapshot research and implementation of multimodal information fusion for data-driven emotion recognition.**\
*Jiang, Y., Li, W., Hossain, M. S., Chen, M., Alelaiwi, A., & Al-Hammadi, M.*\
[*2020*] [Information Fusion]\
[[Paper](https://doi.org/10.1016/j.inffus.2019.06.019)]

**Survey on bimodal speech emotion recognition from acoustic and linguistic information fusion.**\
*Atmaja, Bagus Tris, Akira Sasou, and Masato Akagi.*\
[*2022*] [Speech Communication]\
[[Paper](https://doi.org/10.1016/j.specom.2022.03.002)]

**A review of multimodal emotion recognition from datasets, preprocessing, features, and fusion methods.**\
*Pan, B., Hirota, K., Jia, Z., & Dai, Y.*\
[*2023*] [Neurocomputing]\
[[Paper](https://doi.org/10.1016/j.neucom.2023.126866)]

**Deep Learning Approaches for Bimodal Speech Emotion Recognition: Advancements, Challenges, and a Multi-Learning Model**\
*S. Kakuba, A. Poulose and D. S. Han*\
[*2023*] [IEEE Acess]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.3325037)]

**A comprehensive survey on deep learning multi-modal fusion: Methods, technologies and applications.**\
*T. Jiao, C. Guo, X. Feng, Y. Chen, and J. Song*\
[*2024*] [Computers, Materials & Continua]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

**Multi-modal fusion approaches for tourism: A comprehensive survey of data-sets, fusion techniques, recent architectures, and future directions.**\
*Q. W. Khan, R. Ahmad, A. Rizwan, A. N. Khan, C.-W. Park, and D. Kim*\
[*2024*] [Computers and Electrical Engineering]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

## Data sets
**Cmu-moseas: A multimodal language dataset for Spanish, Portuguese, German and French**\
*A. Zadeh, Y. S. Cao, S. Hessner, P. P. Liang, S. Poria, and L.-P. Morency*\
[*2020*] [Proceedings of the Conference on Empirical Methods in Natural Language Processing. Conference on Empirical Methods in Natural Language Processing]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

**A database of german emotional speech.**\
*F. Burkhardt, A. Paeschke, M. Rolfes, W. F. Sendlmeier, B. Weiss et al.*\
[*2005*] [Interspeech]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

**EMOVO corpus: an Italian emotional speech database**\
*G. Costantini, I. Iaderola, A. Paoloni, and M. Todisco*\
[*2016*] [Proceedings of the Ninth International Conference on Language Resources and Evaluation]\
[[Paper](http://www.lrec-conf.org/proceedings/lrec2014/pdf/591)]

**Iemocap: Interactive emotional dyadic motion capture database,” Language resources and evaluation**\
*C. Busso, M. Bulut, C.-C. Lee, A. Kazemzadeh, E. Mower, S. Kim, J. N. Chang, S. Lee, and S. S. Narayanan*\
[*2008*]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

**The model for end-stage liver disease (meld)**\
*P. S. Kamath and W. R. Kim*\
[*2007*] [Hepatology]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

**The ryerson audio-visual database of emotional speech and song (ravdess): A dynamic, multimodal set of facial and vocal expressions in north american english**\
*S. R. Livingstone and F. A. Russo*\
[*2018*] [PloS one]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

**Recognizing human emotional state from audiovisual signals**\
*Y. Wang and L. Guan*\
[*2008*] [IEEE transactions on multimedia]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]

**Surrey audio-visual expressed emotion (savee) database**
*P. Jackson and S. Haq*\
[*2014*] [University of Surrey: Guildford]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.xxx)]


## Review of fusion methods in SER
### Early fusion

**Late fusion multiview clustering via min-max optimization**\
*M. Li, X. Liu, Y. Zhang, and W. Liang*\
[*2023*] [IEEE Transactions on Neural Networks and Learning Systems]

**Speech emotion recognition via graph-based representations**\
*Pentari, A., Kafentzis, G., Tsiknakis, M.*\
[*2024*] [Scientific Reports]\
[[Paper](https://doi.org/10.1038/s41598-024-52989-2)]

**An efficient feature selection method for arabic and english speech emotion recognition using grey wolf optimizer**\
*Shahin, I., Alomari, O.A., Nassif, A.B., Afyouni, I., Hashem, I.A., Elnagar, A.*\
[*2023*] [Applied Acoustics]

**Fusion-based speech emotion classification using two-stage feature selection.**\
*Xie, J., Zhu, M., Hu, K.*\
[*2023*] [Speech Communication]\
[[Paper](https://doi.org/10.1016/j.specom.2023.102955)]

**Attention guided 3d cnn-lstm model for accurate speech based emotion recognition.**\
*Atila, O., Şengür, A.*\
[*2021*] [Applied Acoustics]\
[[Paper](https://doi.org/10.1016/j.apacoust.2021.108260)]

### Late fusion
**A multi-feature fusion speech emotion recognition method based on frequency band division and improved residual network.**\
*Guo, Y., Zhou, Y., Xiong, X., Jiang, X., Tian, H., Zhang, Q.*\
[*2023*] [IEEE Access]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.32998220)]

**Cross corpus speech emotion recognition using transfer learning and attention-based fusion of wav2vec2 and prosody features.**\
*Naderi, N., Nasersharif, B.*\
[*2023*] [Knowledge-Based Systems]\
[[Paper](https://doi.org/10.1016/j.knosys.2023.110814)]

**A parallel-model speech emotion recognition network based on feature clustering.**\
*Zhang, L.M., Ng, G.W., Leau, Y.B., Yan, H.*\
[*2023*] [IEEE Access]\
[[Paper](https://doi.org/10.1109/ACCESS.2023.3294274)]

**Multiple models fusion for multi-label classification in speech emotion recognition systems**\
*Slimi, Anwer and Hafar, Nafaa and Zrigui, Mounir and Nicolas, Henri*\
[*2022*] [Procedia Computer Science]\
[[Paper](https://doi.org/10.1016/j.procs.2022.09.345)]

**Graph based emotion recognition with attention pooling for variable-length utterances.**\
*Liu, J., Wang, H., Sun, M., Wei, Y.*\
[*2022*] [Neurocomputing]\
[[Paper](https://doi.org/10.1016/j.neucom.2022.05.007)]

**Research on feature fusion speech emotion recognition technology for smart teaching**\
*Zhang, Shaoyun and Li, Chao*\
[2022] [Mobile Information Systems]\
[[Paper](https://doi.org/10.1155/2022/7785929)]

**Multi-type features separating fusion learning for Speech Emotion Recognition**\
*Xu, Xinlei and Li, Dongdong and Zhou, Yijun and Wang, Zhe*\
[*2022*] [Applied Soft Computing]\
[[Paper](https://doi.org/10.1016/j.asoc.2022.109648)]

**Robinnet: A multimodal speech emotion recognition system with speaker recognition for social interactions.**\
*Khurana, Y., Gupta, S., Sathyaraj, R., Raja, S.P.*\
[*2024*] [IEEE Transactions on Computational Social Systems]\
[[Paper](https://doi.org/10.1109/TCSS.2022.3228649)]

**Speech emotion recognition by late fusion for bidirectional reservoir computing with random projection.**\
*Ibrahim, H., Loo, C.K., Alnajjar, F.*\
[*2021*] [IEEE Access]\
[[Paper](https://doi.org/10.1109/ACCESS.2021.3107858)]

**A novel dual attention-based blstm with hybrid features in speech emotion recognition.**\
*Chen, Q., Huang, G.*\
[*2021*] [Engineering Applications of Artificial Intelligence]\
[[Paper](https://doi.org/10.1016/j.engappai.2021.104277)]

**Att-net: Enhanced emotion recognition system using lightweight self-attention module.**\
*Kwon, S., et al.*\
[*2021*] [Applied Soft Computing]\
[[Paper](https://doi.org/10.1016/j.asoc.2021.107101)]

**Speech emotion recognition using fusion of three multi-task learning-based classifiers: HSF-DNN, MS-CNN and LLD-RNN**\
*Yao, Zengwei and Wang, Zihao and Liu, Weihuang and Liu, Yaqian and Pan, Jiahui*\
[*2020*] [Speech Communication]\
[[Paper](https://doi.org/10.1016/j.specom.2020.03.005)]
### Deep fusion

**A multi-feature fusion speech emotion recognition method based on frequency band division and improved residual network.**\
*Guo, Y., Zhou, Y., Xiong, X., Jiang, X., Tian, H., Zhang, Q.*\
[*2023*] [IEEE Access]\
[[Paper](https://doi.org/110.1109/ACCESS.2023.3299822)]

**Speech emotion recognition based on multi-dimensional feature extraction and multi-scale feature fusion**\
*Yu, Lingli and Xu, Fengjun and Qu, Yundong and Zhou, Kaijun*\
[*2024*] [Applied Acoustics]\
[[Paper](https://doi.org/10.1016/j.apacoust.2023.109752)]

**A multi-message passing framework based on heterogeneous graphs in conversational emotion recognition.**\
*Meng, T., Shou, Y., Ai, W., Du, J., Liu, H., Li, K.*\
[*2024*] [Neurocomputing]\
[[Paper](https://doi.org/10.1016/j.neucom.2023.127109)]

**MM DialogueGAT—A Fusion Graph Attention Network for Emotion Recognition Using Multi-Model System**\
*Fu, Rui and Gai, Xiaomei and Abdulhakim Al-Absi, Ahmed and Abdulhakim Al-Absi, Mohammed and Alam, Muhammad and Li, Ye and Jiang, Meng and Wang, Xuewei*\
[*2024*] [IEEE Access]\
[[Paper](https://doi.org/110.1109/ACCESS.2024.3350156)]

**Speech Emotion Recognition Based on Feature Fusion and Residual Graph Convolutional Network**\
*Zhang, Yuanbang and Cui, Lin and Sun, Xiaodong and Xue, Kai*\
[*2023*] [IEEE International Conference on Signal Processing, Communications and Computing (ICSPCC)]\
[[Paper](https://doi.org/10.1109/ICSPCC59353.2023.10400357)]

**Dual memory fusion for multimodal speech emotion recognition**\
*Priyasad, D., Fernando, T., Sridharan, S., Denman, S., Fookes*\
[*2023*] [INTERSPEECH]\
[[Paper](https://doi.org/10.21437/Interspeech.2023-1090)]

**RBA-GCN: Relational Bilevel Aggregation Graph Convolutional Network for Emotion Recognition**\
*Yuan, Lin and Huang, Guoheng and Li, Fenghuan and Yuan, Xiaochen and Pun, Chi-Man and Zhong, Guo*\
[*2023*] [IEEE/ACM Transactions on Audio, Speech, and Language Processing]\
[[Paper](https://doi.org/10.1109/TASLP.2023.3284509)]

**Spatio-temporal representation learning enhanced speech emotion recognition with multi-head attention mechanisms.**\
*Chen, Z., Lin, M., Wang, Z., Zheng, Q., Liu, C.*\
[*2023*] [Knowledge-Based Systems]\
[[Paper](https://doi.org/10.1016/j.knosys.2023.111077)]

**Speech emotion recognition using multi-modal feature fusion network.**\
*Li, F., Luo, J., Liu, W.*
[*2023*] [2023 IEEE 6th International Conference on Pattern Recognition and Artificial Intelligence (PRAI)]\
[[Paper](https://doi.org/10.1109/PRAI59366.2023.10332053)]\

**Improved speech emotion recognition focusing on high-level data representations and swift feature extraction calculation.**\
*Abdusalomov, A., Kutlimuratov, A., Nasimov, R., Whangbo, T.K.*\
[*2023*] [Computers, Materials & Continua]\
[[Paper](https://doi.org/10.32604/cmc.2023.044466.)]

**Self-labeling with feature transfer for speech emotion recognition**\
*Wen, Guihua and Liao, Huiqiang and Li, Huihui and Wen, Pengchen and Zhang, Tong and Gao, Sande and Wang, Bao*\
[*2022*] [Knowledge-Based Systems]\
[[Paper](https://doi.org/10.1016/j.knosys.2022.109589)]

**Head Fusion: Improving the Accuracy and Robustness of Speech Emotion Recognition on the IEMOCAP and RAVDESS Dataset**\
*Xu, Mingke and Zhang, Fan and Zhang, Wei*\
[*2021*] [IEEE Access]\
[[Paper](https://doi.org/10.1109/ACCESS.2021.3067460)]
### Hybrid fusion

## Review of fusion technologies in SER
### Data representation
### Data translation
### Attention mechanism
#### Multi-head attention
#### Cross-modality attention
#### Dual-attention network
#### Graph attention network
### Graph-based fusion

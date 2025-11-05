# Ransomware Classification

**Project Topic:** Ransomware Detection using Image-Based Representation of PE Headers: A Deep Learning Approach

**Author**: Kolawole Oriola, 

**Abstract:**    
The frequency of cyberattacks has risen significantly in the past few years. Cybercrime costs have increased dramatically in recent years and don't appear to be going down. According to a report by leading data and statistics portal Statista, cybercrime is projected to inflict $10.29 trillion in damages on the global economy by 2025. Cyberattacks, such as ransomware attacks, can seriously affect an organization's ability to operate. These attacks can cause significant disruption and financial loss by targeting specific people, groups, nations, or even the entire planet.  To respond to these attacks, this research proposes a ransomware detection method that visualizes Portable Executable (PE) headers as colour images and classifies them using three distinct Convolutional Neural Network (CNN) architectures. This strategy makes feature extraction easier, decreases the processing burden, and is better equipped to counter evasion tactics and adapt to the ever-changing ransomware landscape. Using three datasets the suggested model achieved an accuracy of  93.71%, 96.45%, and 91.54% on the VGG16 model, 92.31%, 90.86%, and 91.76% on the Xception CNN model while the Resnet50 model achieved an accuracy of 87.41%, 86.80%, and 84.82%. This approach was also used to classify ransomware families; VGG16, Xception CNN, and Resnet50 models with an accuracy of 89%, 85%, and 79% respectively. Based on these promising results, this strategy has proven to be an excellent technique for ransomware detection and other forms of cyberattacks.

Link: *coming soon*

**Dataset 3 Overview**    
This dataset combines samples from multiple research sources.
- Ransomware: 2,200 samples from MarauderMap (Hou et al., 2024) and 1,577 from ICFL-UP on GitHub (Dendere & Singh, 2024).
- Goodware: 1,267 benign applications from Moreira et al. (2024), 1,000 from Manavi and Hamzeh (2021c), and 982 from DikeDataset on GitHub.

Description
Comprehensive datasets were difficult to obtain, so I curated and consolidated these resources to support further research. The dataset is now publicly available for academic and practical use.
If you use this dataset, please cite my associated paper — proper attribution is appreciated.

Contents
'pe_headers.csv' – Extracted PE header features.
'extractor.py' – Python script used for feature extraction.

**Reference**  
Dendere, T. R., & Singh, A. (2024). Ransomware detection using portable executable imports. International Conference on Cyber Warfare and Security, 19(1), 66–74. https://doi.org/10.34190/iccws.19.1.2031  

Hou, Y., Guo, L., Zhou, C., Xu, Y., Yin, Z., Li, S., Sun, C., & Jiang, Y. (2024). An Empirical Study of Data Disruption by Ransomware Attacks. ICSE ’24: IEEE/ACM 46th International Conference on Software Engineering. https://doi.org/10.1145/3597503.3639090  

Manavi, F., & Hamzeh, A. (2021c). Ransomware detection based on PE header using convolutional neural networks. Isecure. https://doi.org/10.22042/isecure.2021.262846.595  

Moreira, C. C., Moreira, D. C., & Sales, C. (2024). A comprehensive analysis combining structural features for detection of new ransomware families. Journal of Information Security and Applications, 81, 103716. https://doi.org/10.1016/j.jisa.2024.103716  

https://github.com/iosifache/DikeDataset

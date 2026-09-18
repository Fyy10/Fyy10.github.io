---
title: "Partial Feature Selection and Alignment for Multi-Source Domain Adaptation"
collection: publications
permalink: /publication/2021-06-24-Partial Feature Selection and Alignment for Multi-Source Domain Adaptation
excerpt: 'A work on Multi-Source Domain Adaptation.'
date: 2021-06-24
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition, CVPR 2021, virtual, June 19-25, 2021'
paperurl: # 'https://openaccess.thecvf.com/content/CVPR2021/papers/Fu_Partial_Feature_Selection_and_Alignment_for_Multi-Source_Domain_Adaptation_CVPR_2021_paper.pdf'
citation: # 'Yangye Fu, Ming Zhang, Xing Xu, Zuo Cao, Chao Ma, Yanli Ji, Kai Zuo, and Huimin Lu. Partial Feature Selection and Alignment for Multi-Source Domain Adaptation. In IEEE/CVF Conference on Computer Vision and Pattern Recognition, CVPR 2021, virtual, June 19-25, 2021.'
---

<a href='https://openaccess.thecvf.com/content/CVPR2021/papers/Fu_Partial_Feature_Selection_and_Alignment_for_Multi-Source_Domain_Adaptation_CVPR_2021_paper.pdf'>Download paper here</a>

# Abstract

Multi-Source Domain Adaptation (MSDA), which dedicates to transfer the knowledge learned from multiple source domains to an unlabeled target domain, has drawn increasing attention in the research community. By assuming that the source and target domains share consistent key feature representations and identical label space, existing studies on MSDA typically utilize the entire union set of features from both the source and target domains to obtain the feature map and align the map for each category and domain. However, the default setting of MSDA may neglect the issue of *"partialness"*, i.e., 1) a part of the features contained in the union set of multiple source domains may not present in the target domain; 2) the label space of the target domain may not completely overlap with the multiple source domains. In this paper, we unify the above two cases to a more generalized MSDA task as Multi-Source Partial Domain Adaptation (MSPDA). We propose a novel model termed Partial Feature Selection and Alignment (PFSA) to jointly cope with both MSDA and MSPDA tasks. Specifically, we firstly employ a feature selection vector based on the correlation among the features of multiple sources and target domains. We then design three effective feature alignment losses to jointly align the selected features by preserving the domain information of the data sample clusters in the same category and the discrimination between different classes. Extensive experiments on various benchmark datasets for both MSDA and MSPDA tasks demonstrate that our proposed PFSA approach remarkably outperforms the state-of-the-art MSDA and unimodal PDA methods.

# Bibtex

```bibtex
@InProceedings{Fu_2021_CVPR,
    author    = {Fu, Yangye and Zhang, Ming and Xu, Xing and Cao, Zuo and Ma, Chao and Ji, Yanli and Zuo, Kai and Lu, Huimin},
    title     = {Partial Feature Selection and Alignment for Multi-Source Domain Adaptation},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2021},
    pages     = {16654-16663}
}
```
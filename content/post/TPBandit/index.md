---
title: 😬 Two-phase multi-armed bandit for online recommendation
summary: 2021 IEEE 8th International Conference on Data Science and Advanced Analytics (DSAA 2021)
date: 2021-10-06
authors:
  - Cairong Yan, Haixia Han, Zijian Wang, Yanting Zhang
# tags:
#   - 
#   - 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---
### 🌟Abstract
Personalized online recommendations strive to adapt their services to individual users by making use of both item and user information. Despite recent progress, the issue of balancing exploitation-exploration (EE) remains challenging. In this paper, we model the personalized online recommendation of e-commence as a two-phase multi-armed bandit problem. This is the first time that “big arm” and “small arm” are introduced into multi-armed bandit (MAB), and a two-stage strategy is adopted to provide target users with the most suitable recommendation list. In the first phase, MAB is used to obtain an item subset that users may be interested in from a large number of items. We use item categories as arms instead of individual items in existing related models to control the arm scale and reduce computational complexity. In the second phase, we directly use the items generated in the first phase as arms of MAB and obtain rewards through fine-grained implicit feedback from users. Empirical studies on three real-world datasets show that our proposed method TPBandit performs better than state-of-the-art bandit-based recommendation methods in several evaluation metrics such as Precision, Recall, and Hit Ratio. Moreover, the two-phase method improves the recommendation performance by nearly 50% compared to the one-phase method in the best case.

### 🌟Full Paper 
If you want to read the full paper, plese click the following button👇🏻
<!-- - block: buttons
    content:
      buttons:
        - title: PDF
          icon: arxiv
          url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9564225 -->
{{< cta cta_text="PDF" cta_link="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9564225" cta_new_tab="true" >}}

### Did you find this page helpful? Consider sharing it 🙌

'''
@INPROCEEDINGS{9564225,
  author={Yan, Cairong and Han, Haixia and Wang, Zijian and Zhang, Yanting},
  booktitle={2021 IEEE 8th International Conference on Data Science and Advanced Analytics (DSAA)}, 
  title={Two-Phase Multi-armed Bandit for Online Recommendation}, 
  year={2021},
  pages={1-8},
  doi={10.1109/DSAA53316.2021.9564225}}
'''





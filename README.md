# Github에 올릴 페이지

# Deep Video Super-Resolution

---

## 1) The state-of-the-art VSR

---

Based on [paperwithcode vsr task](https://paperswithcode.com/task/video-super-resolution), this repository contains summary of the state-of-the-art VSR methods.

### The state-of-the-art VSR
| Model             | Published                                                                                                                                                                             | Code                                             | Year | Vid4 Y - 4x (PSNR) |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | ---- | ------------------ |
| RRN-L              | https://arxiv.org/pdf/2008.05765.pdf                                                                                                                                                  | -                                                | 2020 | 27.69              |
| iSeeBetter         | https://link.springer.com/content/pdf/10.1007/s41095-020-0175-7.pdf                                                                                                                   | https://github.com/amanchadha/iSeeBetter         | 2020 | 27.43              |
| PFNL               | https://openaccess.thecvf.com/content_ICCV_2019/papers/Yi_Progressive_Fusion_Video_Super-Resolution_Network_via_Exploiting_Non-Local_Spatio-Temporal_Correlations_ICCV_2019_paper.pdf | https://github.com/psychopa4/PFNL                | 2019 | 27.40              |
| ADNLVSR            | https://www.sciencedirect.com/science/article/pii/S0925231220304550?casa_token=X22LpXpzhPQAAAAA:Zznqj2wrN_7UKydKmmFXYxSCx-K218Xr_9lnUh_yeMLrEexLxoH3B9QSDwSbAXYuwZs_qXpIA1Ym          | -                                                | 2020 | 27.39              |
| EDVR               | https://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Wang_EDVR_Video_Restoration_With_Enhanced_Deformable_Convolutional_Networks_CVPRW_2019_paper.pdf                        | https://github.com/xinntao/EDVR                  | 2019 | 27.35              |
| VSR-DUF            | https://openaccess.thecvf.com/content_cvpr_2018/papers/Jo_Deep_Video_Super-Resolution_CVPR_2018_paper.pdf                                                                             | https://github.com/yhjo09/VSR-DUF                | 2018 | 27.31              |
| RBPN/6-PF          | https://openaccess.thecvf.com/content_CVPR_2019/papers/Haris_Recurrent_Back-Projection_Network_for_Video_Super-Resolution_CVPR_2019_paper.pdf                                         | https://github.com/alterzero/RBPN-PyTorch        | 2019 | 27.12              |
| TDAN               | https://openaccess.thecvf.com/content_CVPR_2020/papers/Tian_TDAN_Temporally-Deformable_Alignment_Network_for_Video_Super-Resolution_CVPR_2020_paper.pdf                               | https://github.com/YapengTian/TDAN-VSR-CVPR-2020 | 2020 | 26.86              |
| FRVSR              | https://openaccess.thecvf.com/content_cvpr_2018/papers/Sajjadi_Frame-Recurrent_Video_Super-Resolution_CVPR_2018_paper.pdf                                                             | -                                                | 2018 | 26.69              |
| WDVR               | https://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Fan_An_Empirical_Investigation_of_Efficient_Spatio-Temporal_Modeling_in_Video_Restoration_CVPRW_2019_paper.pdf          | https://github.com/ychfan/wdvr_ntire2019         | 2019 | 26.62              |
| MDCN               | https://www.sciencedirect.com/science/article/pii/S0925231219314614?casa_token=KHzPCNDE0w4AAAAA:RrG_XJVjt6jqTa1LRHNws_RNqKlc31iai9iwX7iHcBfWnYoOEhidRqZzhtx8HBrkQuunu6FqGlRm          | -                                                | 2019 | 26.49              |
| DDAN               | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8995790                                                                                                                          | -                                                | 2020 | 26.48              |
| SOF-VSR            | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8967249                                                                                                                          | https://github.com/LongguangWang/SOF-VSR         | 2020 | 26.01              |
| DRDVSR             | https://openaccess.thecvf.com/content_ICCV_2017/papers/Tao_Detail-Revealing_Deep_Video_ICCV_2017_paper.pdf                                                                            | https://github.com/jiangsutx/SPMC_VideoSR        | 2017 | 25.88              |
| VESPCN             | https://openaccess.thecvf.com/content_cvpr_2017/papers/Caballero_Real-Time_Video_Super-Resolution_CVPR_2017_paper.pdf                                                                 | -                                                | 2017 | 25.35              |
| Bicubic (Baseline) |                                                                                                                                                                                       |                                                  |      | 23.82              |


- **RRN-L**

![Doc/Image/model1.png)

- **iSeeBetter**

![Doc/Image/model2.png)

- **PFNL**

![Doc/Image/model3.png)

- **ADNLVSR**

![Doc/Image/model4.png)

- **EDVR**

![Doc/Image/model5.png)

- **VSR-DUF**

![Doc/Image/model6.png)

- **RBPN/6-PF**

![Doc/Image/model7.png)

- **TDAN**

![Doc/Image/model8.png)

- **FRVSR**

![Doc/Image/model9.png)

- **WDVR**

![Doc/Image/model10.png)

- **MDCN**

![Doc/Image/model11.png)

- **DDAN**

![Doc/Image/model12.png)

- **SOF-VSR**

![Doc/Image/model13.png)

- **DRDVSR**

![Doc/Image/model14.png)

- **VESPCN**

![Doc/Image/model15.png)

---

## Citation

---

- Isobe, Takashi, Fang Zhu, and Shengjin Wang. "Revisiting Temporal Modeling for Video Super-resolution." arXiv preprint arXiv:2008.05765 (2020).
- Chadha, Aman, John Britto, and M. Mani Roja. "iSeeBetter: Spatio-temporal video super-resolution using recurrent generative back-projection networks." Computational Visual Media (2020): 1-12.
- Yi, Peng, et al. "Progressive fusion video super-resolution network via exploiting non-local spatio-temporal correlations." Proceedings of the IEEE International Conference on Computer Vision. 2019.
- Sun, Wei, and Yanning Zhang. "Attention-guided Dual Spatial-Temporal Non-local Network for Video Super-Resolution." Neurocomputing (2020).
- Wang, Xintao, et al. "Edvr: Video restoration with enhanced deformable convolutional networks." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops. 2019.
- Jo, Younghyun, et al. "Deep video super-resolution network using dynamic upsampling filters without explicit motion compensation." Proceedings of the IEEE conference on computer vision and pattern recognition. 2018.
- Haris, Muhammad, Gregory Shakhnarovich, and Norimichi Ukita. "Recurrent back-projection network for video super-resolution." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2019.
- Tian, Yapeng, et al. "TDAN: Temporally-Deformable Alignment Network for Video Super-Resolution." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2020.
- Sajjadi, Mehdi SM, Raviteja Vemulapalli, and Matthew Brown. "Frame-recurrent video super-resolution." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018.
- Fan, Yuchen, et al. "An Empirical Investigation of Efficient Spatio-Temporal Modeling in Video Restoration." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops. 2019.
- Purohit, Kuldeep, Srimanta Mandal, and A. N. Rajagopalan. "Mixed-dense connection networks for image and video super-resolution." Neurocomputing (2019).
- Li, Feng, Huihui Bai, and Yao Zhao. "Learning a Deep Dual Attention Network for Video Super-Resolution." IEEE Transactions on Image Processing 29 (2020): 4474-4488.
- Wang, Longguang, et al. "Deep Video Super-Resolution using HR Optical Flow Estimation." arXiv preprint arXiv:2001.02129 (2020).
- Tao, Xin, et al. "Detail-revealing deep video super-resolution." Proceedings of the IEEE International Conference on Computer Vision. 2017.
- Caballero, Jose, et al. "Real-time video super-resolution with spatio-temporal networks and motion compensation." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017.
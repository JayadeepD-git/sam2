# SAM 2 based Instrument segmentation
Instrument segmentation from cataract surgery videos

1. Convert video to frames - vid_to_frames.py
2. Annotate an anchor frame with instruments - annotations_prompter.py
3. Segment using SAM 2 - sam2_seg_inst.py


## Acknowledgments
This project utilizes the **Segment Anything Model 2 (SAM 2)** developed by Meta AI for the core instrument segmentation pipeline. 

```bibtex
@article{ravi2024sam2,
  title={SAM 2: Segment Anything in Images and Videos},
  author={Ravi, Nikhila and Gabeur, Valentin and Hu, Yuan-Ting and Hu, Ronghang and Ryali, Chaitanya and Ma, Tengyu and Khedr, Haitham and R{\"a}dle, Roman and Rolland, Chloe and MacNicol, Laura and others},
  journal={arXiv preprint arXiv:2408.00714},
  year={2024}
}

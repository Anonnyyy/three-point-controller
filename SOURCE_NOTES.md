# Content provenance

This page is a private project showcase, based on the supplied manuscript and video. It is not a claim of publication or code release.

| Material | Source |
| --- | --- |
| Paper PDF | `01三点控制器/review/_最终提交！！/root_first_8_pages_fixed_v2.pdf` (8 pages, copied unchanged) |
| Method and terminology | `review/Async_lym_4_reviewer_diff/sections/overview.tex`, Sections III and IV |
| Tracking table | Manuscript Table I; displayed means only; all-rollout statistics including failures |
| OOD results | Experimental Results: OOD Post-Training with MPC Completion; 80 post-training / 40 held-out motions |
| Online planning | Experimental Results: Closed-loop Online Manipulation; 12/25 vs. 6/25 are complete pipeline results |
| Hardware results | Experimental Results: Real-world Hardware Experiments; distinguish 60/70 overall from 25/25 vs. 21/25 matched subset |
| Video | `01三点控制器/ppt_video/0918终版.mp4`, copied unchanged, duration 207.888 s |
| Poster | Unmodified full video frame extracted at 190 s |
| Figures | Original manuscript `Picture/whole6.png`, `Picture/4motion.jpg`, `Picture/post-train-compare-addtext.png`, `Picture/vla.png`, `data/ood12_post_3pic.png` |

The video chapter links seek to representative points in the original video; they do not replace or edit it. The page uses current manuscript numbers when rounding differs in the video.

The page distinguishes ASYNC-3PT from completion-augmented ASYNC-CA. The policy retains the full cached reference and a phase-aligned reference token. Drift predictions are not applied as online reference corrections.

Visual structure references: [OmniH2O](https://omni.human2humanoid.com/) and [HumanPlus](https://humanoid-ai.github.io/). Their content, figures, and implementation were not copied. All scientific media on this page come from the supplied project.

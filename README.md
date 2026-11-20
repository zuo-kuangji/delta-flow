# Δ Flow Matching for Robot Foundation Models

Learn the change from recent history.

[Project website](https://zuo-kuangji.github.io/delta-flow/) · [Paper](https://arxiv.org/abs/2610.15794) · [Official code repository](https://github.com/NTUMARS/delta-flow-matching) · [Citation](#citation)

![Δ-flow overview](docs/static/images/teaser.png)

Δ-flow starts flow matching from recent history plus mild noise and learns the residual change. The project page presents results for ImageWAM, Fast-WAM and π0.5, together with interactive illustrations of flow time and action-chunk continuity.

## Website development

The website uses plain HTML, CSS and JavaScript and needs no build step.

```bash
python3 -m http.server 8000 --directory docs
```

Open http://localhost:8000 in your browser.

## Deployment

GitHub Pages publishes `main` → `/docs`. Updates to files in `docs/` are deployed after pushing to `main`.

## Citation

```bibtex
@article{zuo2026deltaflow,
  title   = {$\Delta$ Flow Matching for Robot Foundation Models},
  author  = {Zuo, Kuangji and An, Tuo and Guo, Xinying and Li, Gen and
             Zhao, Mengfei and Bai, Jiaqi and Lyu, Bofan and Yu, Zhuoyuan and
             Yang, Jinghan and Li, Jiayi and Jia, Jindou and Yang, Jianfei},
  journal = {arXiv preprint arXiv:2610.15794},
  year    = {2026},
  url     = {https://arxiv.org/abs/2610.15794}
}
```

MARS Lab, Nanyang Technological University.

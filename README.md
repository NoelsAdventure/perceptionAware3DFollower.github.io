# Distributed 3D Leader–Follower Formation Control with Field-of-View Safety via Control Barrier Functions

Project website for our paper on **perception-aware safe 3D leader–follower formation control** for multi-UAV systems.

We propose a distributed control framework that lets a follower drone track a leader in 3D while guaranteeing the leader stays inside the follower's onboard camera view at all times — even during aggressive maneuvers and even when the desired formation conflicts with what the camera can see.

> **Live site:** https://noelsadventure.github.io/perceptionAware3DFollower.github.io/

## Authors

- [Immanuel R. Santjoko](https://noelsadventure.my.id)<sup>1†</sup>
- [Richie R. Suganda](https://www.linkedin.com/in/richie-ryulie-585609237/)<sup>1†</sup>
- [Bin Hu](https://binhu85.github.io/)<sup>1,2</sup>

<sup>1</sup> Department of Electrical and Computer Engineering, University of Houston
<sup>2</sup> Department of Engineering Technology, University of Houston
<sup>†</sup> Equal contribution

## Repository structure

```
.
├── index.html          # Main project website
├── oldindex.html       # Previous version (kept for reference)
├── static/
│   ├── css/            # Bulma + custom styles
│   ├── js/             # Bulma carousel/slider, FontAwesome
│   ├── images/         # Figures from the paper
│   └── videos/         # Simulation and hardware experiment videos
└── README.md
```

The `references/` folder (paper PDF and LaTeX source) is **gitignored** and not published.

## Running locally

The site is plain static HTML — no build step needed. Just open `index.html` in a browser, or serve the folder with any static server, for example:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Citation

If you find this work useful, please cite:

```bibtex
@article{santjoko2026perceptionaware3dlff,
  author  = {Santjoko, Immanuel R. and Suganda, Richie R. and Hu, Bin},
  title   = {Distributed 3D Leader--Follower Formation Control with
             Field-of-View Safety via Control Barrier Functions},
  journal = {Under Review},
  year    = {2026},
}
```

## Acknowledgements

Research supported by the University of Houston. Website template adapted from the [Nerfies](https://github.com/nerfies/nerfies.github.io) project.

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

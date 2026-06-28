# MIPU Project Page

Project page for **"The Mirage of Optimizing Training Policies: Monotonic Inference Policies as the Real Objective for LLM Reinforcement Learning"**.

Live site: [https://anitaleungxx.github.io/MIPU/](https://anitaleungxx.github.io/MIPU/)

## About

This page presents **MIPU (Monotonic Inference Policy Update)**, a new policy optimization framework for LLM reinforcement learning. MIPU addresses the training-inference mismatch problem by directly optimizing the deployed inference policy rather than the training-side surrogate.

## Paper

- **arXiv**: [https://arxiv.org/abs/XXXX.XXXXX](https://arxiv.org/abs/XXXX.XXXXX) (placeholder, update after arXiv release)
- **PDF**: [https://arxiv.org/pdf/XXXX.XXXXX.pdf](https://arxiv.org/pdf/XXXX.XXXXX.pdf) (placeholder, update after arXiv release)

## Repository Structure

```
.
├── index.html              # Main project page
├── static/
│   ├── css/                # Bulma + custom styles
│   ├── images/             # Figures and assets
│   ├── js/                 # Scripts
│   └── pdfs/               # Paper PDF (add after arXiv release)
└── README.md
```

## Local Development

To preview the page locally:

```bash
cd /path/to/MIPU
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## License

This website is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

The page was built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template).

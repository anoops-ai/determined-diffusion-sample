## Sample for textual inversion

### Source code is from this [repo](https://github.com/garrett361/determined/tree/stable-diffusion-shared/examples/diffusion/textual_inversion_stable_diffusion)

### Pre-reqs

- Access to [Determined Cluster](https://www.determined.ai/) (Tested this example against V100 GPU's)
- HF Access Token
  - Have a [Huggingface account](https://huggingface.co/join).
  - Have a [Huggingface User Access Token](https://huggingface.co/docs/hub/security-tokens).
  - Accept the Stable Diffusion license (click on *Access repository* [in this link)](https://huggingface.co/CompVis/stable-diffusion-v1-4).

### Launch Notebook
launch notebook via [Determined CLI](https://docs.determined.ai/latest/interfaces/notebooks.html?highlight=notebooks)

- `det notebook start  --config-file notebook.yaml --context .`
- Follow/Run demo.ipynb in notebook

More details are available in this [readme](https://github.com/garrett361/determined/tree/stable-diffusion-shared/examples/diffusion/textual_inversion_stable_diffusion#readme)

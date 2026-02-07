# Working on ViT-decorr (this repo)

Short checklist for each time you want to experiment with Vision Transformers and the decorr (decorrelation) code.

## 1. Go to this repo

```bash
cd /vol/biomedic3/ew1724/ImperialPhD/Research/vit-pytorch
```

## 2. Use the right branch

```bash
git checkout vit-decorr
git branch --show-current   # should print: vit-decorr
```

## 3. Activate the conda env

```bash
conda activate /vol/biomedic3/ew1724/conda_envs/vit-pytorch
```

## 4. Work

Edit code, run scripts (e.g. `train_vit_decorr.py`), try examples from the main README, use `vit_with_decorr` for experiments. This directory is your playground.

## 5. Save and push (when you want to keep changes)

```bash
git add .
git status
git commit -m "Short description of what you did"
git push origin vit-decorr
```

---

**Reminder:** This folder is a **separate Git repo** (your fork of lucidrains/vit-pytorch). All ViT-decorr work and commits happen here, not in the parent ImperialPhD repo.

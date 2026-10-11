# TBT Forward Simulation v0.2 (research prototype)

Purely hypothetical passive 48-DOF cervical/TMJ equilibrium model. **No human measurements, anatomical validation, clinical safety inference, treatment-force recommendations, or high-speed thrust dynamics.**

**Start here:** [Korean README](README_KO.md) · [Biomechanics specification](docs/BIOMECHANICS_MODEL_V02.md).

```sh
pip install -e ".[dev]"
python -m tbt_research simulate --upper 1 --lower 4 --force-scale 3 --out results/custom
pytest -q
```

Open the standalone offline graphical dashboard at `viewer/TBT_simulation_v0_2_OFFLINE.html`. It contains 160 precomputed parameter-sweep states with adjustable constraints and loads. Read `NOTICE.md` before redistribution. This repo intentionally excludes the user-supplied original TBT HTML and private v4 companion.
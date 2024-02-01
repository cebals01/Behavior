# Behavior
Documentation

---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: allensdk
---
```{code-cell} ipython3
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
```
```{code-cell} ipython3
from allensdk.core.brain_observatory_cache import BrainObservatoryCache
manifest_file = '../../../data/allen-brain-observatory/visual-coding-2p/manifest.json'
boc = BrainObservatoryCache(manifest_file=manifest_file)
```

# Behavior Documentation

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from allensdk.core.brain_observatory_cache import BrainObservatoryCache

%matplotlib inline

manifest_file = '../../../data/allen-brain-observatory/visual-coding-2p/manifest.json'
boc = BrainObservatoryCache(manifest_file=manifest_file)

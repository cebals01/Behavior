## Documentation

### Pipeline for 2P and behavior.
#### Initial Mapping         
0 - zstack with 

### Pipeline for 2P and behavior.
/Users/cebals01/Dropbox (Personal)/_nPROJECTS/Olfaction/_CODE/_Data/traits_p3GUI/Developing/2P_StimAndRecord.py
/Users/cebals01/Dropbox (Personal)/_nPROJECTS/Olfaction/_RESULTS/KatyaExps.ai
/Users/cebals01/Dropbox (Personal)/_nPROJECTS/Olfaction/_CODE/_Data/Copilot/4_2PImagingAndStim.ipynb

- Preprocessing

1 - Update dictionary      
2 - Run suite2p for motion correction      
3 - Extract triggers from Trials that had imaging        
    result: ["DATA_folder"] + mouse_name + '_dict_triggers'      

- Behavior      

1 - Load triggers for TIFFs frames extraction.        
2 - Generate files for each trial, raw and motion correction data               
    result_1 : ["trials_arrays_folder"] + mouse_name + '_' + trialkey + '_trial_frames_arr.npy'                           
    result_2 : ["trials_arrays_folder"] + mouse_name + '_' + trialkey + '_trial_frames_arr_mc.npy'                     
3 - Check raw and check             
4 - avg_imgs_after_stim_mc              
5 - 








Markdown is an easy to read and write text format:

- It's _plain text_ so works well with version control
- It can be **rendered** into HTML, PDF, and more
- Learn more at: <https://quarto.org/docs/authoring/>

## Code Cell

Here is a Python code cell:

```{python}
import os
os.cpu_count()
print('hello')
```

## Equation

Use LaTeX to write equations:

$$
\chi' = \sum_{i=1}^n k_i s_i^2
$$

- AttributeError: 'int' object has no attribute 'item'

```
# use np.array to convert it to numpy type
np.array(pipe.scheduler.timesteps[0]).item()
```

- cannot import name 'SAFE_WEIGHTS_NAME' from 'transformers.utils'

```
# reinstall diffusers
pip install diffusers==0.12.1
```
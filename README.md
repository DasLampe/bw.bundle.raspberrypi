# Raspberry PI Config via Bundlewrap

## Example config
```python
nodes['foobar'] = {
    'metadata': {
        'raspberrypi': {
            'config': {
                'gpu_mem': '256',
            },
            'specialConfig': {
                'pi4': {
                    'dtoverlay': 'vc4-fkms-v3d,cma-265',
                },
            },
        },
    },
}
```
### Simple module to disable built-in GMS props and GMS attestation block allowing custom Fingerprint and Keybox to function properly

## How
By editing build.prop
```
persist.sys.pihooks.disable.gms_props
persist.sys.pihooks.disable.gms_key_attestation_block
```

### May work with other LOS based roms and any roms if use the same props

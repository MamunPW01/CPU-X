# Dmidecode: Desktop Management Interface table related utilities

Distributed under the terms of the [GNU GPL v2](https://github.com/X0rg/CPU-X/blob/master/src/dmidecode/LICENSE).

### CPU-X NOTE

This sofware has been patched to be used within CPU-X.  
You can find the official web page of this project here: https://savannah.nongnu.org/projects/dmidecode/  
This is based on dmidecode 3.4+[a1a2258](https://git.savannah.gnu.org/cgit/dmidecode.git/commit/?id=a1a2258ffbe450e8561ee833787da9321fa734b0).

This software is used to retrieve following data:

- CPU tab
  - Package
  - Bus speed (fallback)
- Motherboard tab
  - Motherboard manufacturer
  - Motherboard model
  - Motherboard revision
  - BIOS brand
  - BIOS version
  - BIOS date
  - BIOS ROM size

You can reproduce the output of `dmidecode` command by using `cpu-x --dmidecode`.  
It will dump all DMI data on standard output.  
Note: you can increase dmidecode verbosity by using `cpu-x --verbose --dmidecode`.

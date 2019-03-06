# iMapSplice.simg
repository for singularity image of iMapSplice

put the `Singularity` recipe file into your directory and build an image (if you have root access):
```bash
singularity build iMapSplice.simg ./Singularity
```

Alternatively, retrieve the pre-built image from singularity hub:
```bash
singularity pull -n iMapSplice.simg shub://cory-weller/iMapSplice.simg
```

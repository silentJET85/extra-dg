# extra-dg

This repository has extra packages for `deb-get`. These can include pre-releases, betas, drivers and other things not suitable for deb-get's own repository.
<br> You can view the list of available apps [here](APPS.md).
  
  
## Installation
1. If you haven't already, install `deb-get` by following [their instructions](https://github.com/wimpysworld/deb-get#install).
2. Create the repo file:
        
    ```echo "https://raw.githubusercontent.com/silentJET85/extra-dg/master/02-extra" | sudo tee "/etc/deb-get/02-extra.repo"```

    *(You can replace the `02` in the `02-extra.repo` with any number from 02 to 98 to change the priority. [More info here.](https://github.com/wimpysworld/deb-get#adding-external-repositories) You can also change the `-extra` to something else if you wish.)*

3. Do an update: 

    ```deb-get update```




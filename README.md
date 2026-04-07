# extra-dg

This repository has extra packages for `deb-get`. These can include pre-releases, betas, drivers and other things not suitable for deb-get's own repository.
  
  
## Installation
1. If you haven't already, install `deb-get` by following [their instructions](https://github.com/wimpysworld/deb-get#install).
2. Create the repo file:
        
    ```cat <<< "https://raw.githubusercontent.com/silentJET85/extra-dg/master" | sudo tee "/etc/deb-get/02-extra.repo"```

    *(You can replace the `02` in the filename with any number from 02 to 98 to change the priority. [More info here.](https://github.com/wimpysworld/deb-get#adding-external-repositories) You can also change the `-extra` in the filename to something else if you wish.)*

3. Do an update: 

    ```deb-get update```




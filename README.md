# docker-rhel53-veredas
Create a Docker's minimum image of the head node of the HPC cluster
"veredas" (http://www.cenapad.ufmg.br).
This is done with the help of the shell script, mkimage-yum-rhel53dev.sh,
created from file [mkimage.sh](https://github.com/moby/moby/blob/master/contrib/mkimage.sh) of docker repository. The shell script calls
[yumbootstrap](https://github.com/dozzie/yumbootstrap) to install Red Hat Enterprise Linux 5.3  packages (local repository) in the chroot.

## Development
See [CONTRIBUTING](CONTRIBUTING.md)

## History
See [CHANGELOG](CHANGELOG.md)

## Credits
See [AUTHORS](AUTHORS.md)

## License
See [LICENSE](LICENSE)

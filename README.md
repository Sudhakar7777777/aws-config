aws-config.git
==============
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure your `bash` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/Sudhakar7777777/aws-config.git
ln -sb aws-config/.screenrc .
ln -sb aws-config/.bash_profile .
ln -sb aws-config/.bashrc .
ln -sb aws-config/.bashrc_custom .
mv .emacs.d .emacs.d~
ln -s aws-config/.emacs.d .
```


# stegastamp-awesome

## Quick start

### Init env

#### Python

```sh
git clone https://github.com/pyenv/pyenv.git ~/.pyenv

git clone https://github.com/pyenv/pyenv-virtualenv.git  ~/.pyenv/plugins/pyenv-virtualenv
```

```sh
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc

if which pyenv-virtualenv-init > /dev/null; then eval "$(pyenv virtualenv-init -)"; fi
```

```sh
source ./.zshrc
```

```sh
export v=3.6.12; wget https://npm.taobao.org/mirrors/python/$v/Python-$v.tar.xz -P ~/.pyenv/cache/; pyenv install $v 
```


#### StegaStamp

```sh
git clone --recurse-submodules https://github.com/tancik/StegaStamp.git

cd StegaStamp
```

```sh

```

# pacta-cli

**DEPRECATED: Superseded by https://github.com/jdhoffa/pacta-cli**

Command line tools to work with pacta repositories.

### Installation

* Clones this repo wherever you want.

```bash
git clone https://2DegreesInvesting/pacta-cli.git
```

* Add your chosen path to your `$PATH` in your ~/.bashrc, ~/.zshrc, or similar.

```bash
cd pacta-cli
echo 'export PATH='"$(pwd)"':${PATH}' >> ~/.zshrc
```

### Setup

To make a directory a member of the pacta family add a file ".pacta" in its root.

### Examples

```bash
pacta-find ~/git

pacta-pull-origin-master
```

<img src=http://i.imgur.com/iMh5lHd.png width=700>

### System requirements

pacta-cli is developed is develop for Linux. If you have a different system
and experience problems, consider using it from a docker container.

```bash
docker pull ubuntu
docker run --rm -it ubuntu

# See installation instructions above
```


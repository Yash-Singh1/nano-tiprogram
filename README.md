# `nano-tiprogram`

Syntax highlighting for the TI Calculator Programs in the `nano` code editor.

## Installation

Run:

```sh
git clone https://github.com/Yash-Singh1/nano-tiprogram.git
cd nano-tiprogram/
```

Then run:

### Ubuntu/Debian

```sh
sudo cp tiprogram.nanorc /usr/share/nano/
```

### Mac

```sh
sudo -i
mkdir /usr/local/share/nano/
echo 'include "/usr/share/nano/*.nanorc"' >> /etc/nanorc
cp tiprogram.nanorc /usr/local/share/nano/
```

### Windows

<!-- markdownlint-disable-next-line MD036 -->
**Note: Remember to run as administrator**

```sh
cp tiprogram.nanorc /usr/share/nano/
```

## Usage

Creating and editing a `.tiprogram` file should be syntax highlighted.

# Beaglebone Black Yocto Workspace

## Checkout

Workspace for building custom image for the Beaglebone Black.

git clone https://github.com/cweave72/beaglebone_lab.git
git submodule update --init --recursive

## Build init

Use the init_ws.sh script to initialize/activate the build workspace.

After a clean checkout, to initialize the build workspace using the meta-bbb-lab
template:

```bash
. init_ws.sh --init [builddir (default:buld)]
```

To simply activate the environment (previously ran `--init`):

```bash
. init_ws.sh
```

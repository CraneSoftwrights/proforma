# PROFORMA project

A proforma wood-burning project to copy as a starting point for a new project.

This file requires the one substitution of the string `PROFORMA` into a short filename component (e.g. `board-baseball`, `revenge`, `phone-stand`, etc.):

- `.github/workflows/build.yml` - a hidden git system file that orchestrates the build process

These files must be re-worked from scratch (note the use of `PROFORMA` in the file):

- `design/design-PROFORMA.svg` - the main design file directing output creation
- `shared/outputs-readme.txt` - the README file used in the output ZIP file base directory
- `README.md` - the main README file describing your work
- `LICENSE` - the license file for your work

You may choose to revise the `README.md` files in the subdirectories, though there are short descriptions in each already.

Also included, without any changes needed, are these handy files for cutting up raw boards:
- `cuts/svg/*.svg` - sources of pre-shaped cuts for convenience
- `cuts/pdf/*.pdf` - burn files of pre-shaped cuts for convenience

This file need not be touched, but is described here for information and a reminder:
- `.gitignore` - a hidden git system file not to be overlooked when copying this repository

Of course you may add any other files you wish. The above files are the ones found in this source repository.

Your GitHub repository configuration settings needs the following:

- Actions / General / Workflow permissions / Read and write permissions / Save
- 


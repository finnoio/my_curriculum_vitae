### MacOS Compilation

#### Compact TeX distribution
To use a compact TeX distribution as an alternative to the full TeX Live / MacTeX, run:
```bash
brew install basictex
```

#### Install Liberation Fonts
```bash
brew install --cask font-liberation
```

#### Install TeX Packages
Update the package manager and install required TeX packages:
```bash
tlmgr update --self
tlmgr install enumitem
tlmgr install ulem
tlmgr install titlesec
tlmgr install fontspec
```

#### Compile CV
```bash
xelatex CV.tex
```

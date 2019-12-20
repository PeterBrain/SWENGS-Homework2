# SWENGS-Homework2

## Setup Guide
### Cloning & submodules
There are two ways to clone the repository with submodules:
1. cloning step-by-step
2. cloning all-in-one command

#### 1 - step-by-step
```bash
git clone https://github.com/PeterBrain/SWENGS-Homework2.git
cd SWENGS-Homework2
git submodule init
git submodule update
```

#### 2 - all-in-one
```bash
git clone --recurse-submodules https://github.com/PeterBrain/SWENGS-Homework2.git
cd SWENGS-Homework2
```
This will automatically clone the repo, plus all the submodules.

Also check out the README file in the `Backend` submodule for further setup instructions.

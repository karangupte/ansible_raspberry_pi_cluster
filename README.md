# Ansible playbook to set up your Raspberry Pi cluster

### Install Python if you don't already have it

```bash
brew install python3 pip3-python
```

### Install Anaconda 

On OS X, you can use Homebrew to install anaconda 

```bash
brew cask install anaconda 
```

### Set up a Python virtual environment for ansible 
Create the environment 
```bash
conda create --name ansible_venv python=3.7
```

..activate it 
```bash
conda activate ansible_venv
```

... and install ansible in this environment 
```bash
conda install -c conda_forge ansible
```

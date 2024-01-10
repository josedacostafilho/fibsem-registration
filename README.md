# fibsem-registration

Software for preprocessing and registration of FIBSEM data.

## Installation
1. Open a terminal window
2. If you do not have miniconda installed, download it via
```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```
and install it.
```bash
bash Miniconda3-latest-Linux-x86_64.sh
```
Type `conda` to check whether the installation worked.
3. Clone the repository to your machine
```bash
git clone https://github.com/josedacostafilho/fibsem-registration ~/your_folder
```
and navigate to its folder.
```bash
cd ~/your_folder/fibsem-registration
```
5. Create the conda environment
```bash
conda env create -f environment.yml
```

## Usage
1.Activate the conda environment
```bash
conda activate registration
```
2. Go to the repository folder and run
```bash
python gui.py
```


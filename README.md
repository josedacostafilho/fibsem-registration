# fibsem-registration

Software for preprocessing and registration of FIBSEM data. It can be run as an executable or as a Python script.

## 1. Using executable file
On a terminal window, navigate to 
```bash
fibsem-registration/dist/gui
```
and run
```bash
./gui
```

## 2. Python script

### Installation
#### 1. Open a terminal window
#### 2. (Optional) Install Miniconda
If you do not have Miniconda installed, download it via
```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```
and install it.
```bash
bash Miniconda3-latest-Linux-x86_64.sh
```
Type `conda` to check whether the installation worked.
#### 3. Clone the repository to your machine
```bash
git clone https://github.com/josedacostafilho/fibsem-registration ~/your_folder
```
#### 4. Navigate to the repository folder and create the conda environment
```bash
conda env create -f environment.yml
```

### Usage
#### 1. Activate the conda environment
```bash
conda activate registration
```
#### 2. Go to the repository folder and run
```bash
python gui.py
```
#### 3. Follow the GUI instructions
Note that your data should be organized as a sequence of 2D .tif files inside some folder, with pixel intensities ranging from 0 to 255. For preprocessing, background areas can be masked with either 0 or 255. For registration, masking is done with 255.


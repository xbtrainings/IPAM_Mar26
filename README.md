# IPAM March 5-6, 2026

## Xavier Bresson

<br><br> 

### Cloud Machine : Google Colab (Free GPU)

* Follow this Notebook installation :<br>
https://colab.research.google.com/github/xbtrainings/IPAM_Mar26/blob/main/installation/installation.ipynb

* Open your Google Drive :<br>
https://www.google.com/drive

* Open in Google Drive Folder 'IPAM_Mar26_codes'<br>
Select any notebook 'file.ipynb' and open it with Google Colab using Control Click + Open With Colaboratory

<br><br>

### Local Installation for OSX M Chips

* Open a Terminal and type

```sh
   # Conda installation
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o miniconda.sh -J -L -k # OSX M
   chmod +x miniconda.sh
   ./miniconda.sh
   source ~/.bashrc

   # Clone GitHub repo
   git clone https://github.com/xbresson/IPAM_Mar26.git
   cd IPAM_Mar26

   # Install python libraries
   conda env create -f environment_osx_arm64.yml
   conda activate deeplearn_course

   # Run the notebooks in Chrome
   jupyter notebook
   ```

### Local Installation for Windows 

```sh
   # Install Anaconda 
   https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

   # Open an Anaconda Terminal 
   Go to Application => Anaconda3 => Anaconda Prompt 

   # Install git : Type in terminal
   conda install git 

   # Clone GitHub repo
   git clone https://github.com/xbresson/IPAM_Mar26.git
   cd IPAM_Mar26

   # Install python libraries
   conda env create -f environment_win64.yml
   conda activate deeplearn_course

   # Run the notebooks in Chrome
   jupyter notebook
   ```



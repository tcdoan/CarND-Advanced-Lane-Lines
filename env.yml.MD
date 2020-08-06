# Setup steps that works with env.yml

####  Download Anaconda3-4.3.1
1. On Linux https://repo.anaconda.com/archive/Anaconda3-4.3.1-Linux-x86_64.sh
2. Windows: https://repo.anaconda.com/archive/Anaconda3-4.3.1-Windows-x86_64.exe 

####  Setup Anaconda3-4.3.1-Windows-x86_64.exe
- Use user setup not system setup mode
- Location: C:\Users\thdoa\AppData\Local\Continuum\Anaconda3

####  Create environment 
- conda env create -f env.yml
- activate carndp2

#### Remove env 
- \[source\] deactivate
-  conda remove --name MyEnvName --all


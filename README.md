# Synchronisateur de dossier fichier local--> disk dur externe 
![Project Status](https://img.shields.io/badge/status-active-brightgreen)  
![License](https://img.shields.io/badge/license-MIT-blue)


```
                       _                     _           _   _             
                      | |                   (_)         | | (_)            
  ___ _   _ _ __   ___| |__  _ __ ___  _ __  _ ___  __ _| |_ _  ___  _ __  
 / __| | | | '_ \ / __| '_ \| '__/ _ \| '_ \| / __|/ _` | __| |/ _ \| '_ \ 
 \__ \ |_| | | | | (__| | | | | | (_) | | | | \__ \ (_| | |_| | (_) | | | |
 |___/\__, |_| |_|\___|_| |_|_|  \___/|_| |_|_|___/\__,_|\__|_|\___/|_| |_|
       __/ |                                                               
      |___/                                                                

                                                    
```
Ce projet est un script qui permet depuis un terminal de sélectioner un dossier dans le /home/user et de le cloner sur un disque dur externe avec la meme architecture et en ajoutant un systeme de versions.Crée pour fonctioner sur un terminal unix.
## Installation

Clonez le dépôt :

```bash
git clone https://github.com/phile098/synchronisation.git
cd synchronisation

```
# Droit d'execution

```bash
chmod 777 script_synchro.py

```
# instalation des module

```bash
pip install shutil
pip install tqdm

```
# Argument argparse 
```bash
--interactive
--source
--destination
--version
```
# Utilisation en ligne direct dans le terminal 

```bash
python3 chemin_du_script/script_syncro.py --source /chemin_du_dossier_a_synchro --destination /chemin_du_disk_externe
```
# Utilisation interactive
```bash
python3 chemin_du_script/script_syncro.py --interactive
```

# Example 
![Mon image](/script.png)

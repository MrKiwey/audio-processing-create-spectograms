To use this repo to create spectograms from sound files, you need to clone this repo to your computer.

Then it is possible to create a virtual environment to install the packages you need. 

To do this, run this code from the terminal after cloning:

```
python -m venv your-venv-name
```

Then install librosa, pandas and matplotlib:

```
pip install librosa, pandas, matplotlib
```

You also need to download your sound files and put them in the project folder. Remember to change the filepath to the path of the folder where you put the sound files.

Once you have done these steps you are ready to create some mel spectograms!

# Forays-into-ML
Testing out various ML projects
Blur and Clear is based off of (a fork and edited copy of) https://github.com/aditya9211/Blur-and-Clear-Classification

### Whats new with this version
The jupyter notebook has the most detailed comments - explains the quick start
#### Major changes implemnted in the jupyter notebook
*The original scripts have not been changed! if you just run those you will probably not get the same results
- `yml` was added - this is for creating a conda env, will still have to pip install the requirements.txt
- import functions rather than running the scripts - move through the notebook this way and can change the `config.py` hyper-parameters in the notebook
- args have been removed for the `train.py` and given hard encoding in the notebook
- in the `predict.py` part there is a new ability to direct the model to a folder of images - based on prediction the script will copy the image to a corresponding folder. *can change the `shutil.copy` to `shutil.move` to save disk space if you are sure about the results.
- some `%%time` commands were inserted so you can see how long each training of the model and prediction takes

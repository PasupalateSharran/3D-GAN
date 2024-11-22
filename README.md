# 3D-GAN

#### Training
* `pip install -r requirements.txt`
* `cd src`, run `python main.py` on GPU. 

* During training, model weights and some 3D reconstruction images would be also logged to the `outputs` folders, respectively, for every `model_save_step` number of step in `params.py`. You can play with all parameters in `params.py`.

#### Evaluation
* For evaluation for trained model, run `python main.py --test=True` to call `tester.py`.
* To visualize using visdom, first run `python -m visdom.server`, then `python main.py --test=True --use_visdom=True`.
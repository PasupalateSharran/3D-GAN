# 3D-GAN

#### Training
* `pip install -r requirements.txt`
* `cd src`, run `python main.py` on GPU.
  
* For evaluation for trained model, run `python main.py --test=True` to call `tester.py`.
* To visualize using visdom, first run `python -m visdom.server`, then `python main.py --test=True --use_visdom=True`.

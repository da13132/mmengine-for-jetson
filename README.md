# mmengine-for-jetson
This mmengine comments out the part about torch.distributed in mmengine/mmengine/dist/utils.py and mmengine/mmengine/dist/dist.py, which is used to solve the cannot import name 'ProcessGroup' after installing mmdeploy in jetson Error from 'torch.distributed'

Forgive my clumsy upload operation, after downloading mmengine-0.8.4.zip, upload it to jetson and build it locally, using method:

`unzip mmengine-0.8.4.zip` <br>
`cd mmengine-0.8.4` <br>
`pip install -v -e .` <br>

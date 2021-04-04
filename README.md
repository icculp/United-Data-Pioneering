# United-Data-Pioneering
Project #4 - Impervious Surfaces

Using anaconda with python3.6 and tensorflow-gpu 1.5

Setup was a bit of a pain;

	conda create --name {envname} python=3.6
	conda install ipykernel --name {envname}
	python -m ipykernel install --prefix=C:/anaconda/envs/{envname} --name {envname}
	activate envname

	python -m pip install tensorflow-gpu==1.5
	
	conda install -c anaconda cudatoolkit=9.0
	
	conda install cuDNN=7.6.0
	
	Then with many incompatible dependency versions, I ended up with the package versions exported from pip freeze found in requirements.txt, which can be installed by python -m pip install -r requirements.txt
	
	I can get to the training step, last I left it it was stuck on output "Epoch 1/12"
	
	checkpoint.h5 too large to upload to github

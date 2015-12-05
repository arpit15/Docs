## ae-cnn-featuremaps
Project for training NN for identification of image location.<br>

See the inital project guideline on [evernote](https://www.evernote.com/shard/s200/sh/1e5f0910-f082-4caf-b463-a918272a4640/39d3cdea726a5ce6835fb3f87804efd3).
<br>
#Pre-requisites
`sudo apt-get install python-numpy python-scipy python-dev python-pip python-nose g++ libopenblas-dev git h5py Image scikit-image matplotlib Pillow glob2`<br>
`sudo pip install Theano`<br>


<h1>HDF5 SCRIPTS</h1><br>
--scripts_hdf<br>
	--img2dataset.py<br>
	containing scipts to create image dataset in hdf5 format 
--theano_scripts<br>
	--dA.py<br>
	to train the autoencoder given h5dump<br>
	--read_h5.py<br>
	to visualize the patch with its entropy

<h1>Demo</h1><br>
`python theano_scripts/read_h5.py` <br>
to visualize the patches<br>
`python theano_scripts/dA.py`<br>
to train the autoencoder and Denoising autoencoder <br>
dA_plots - contains the filters as images



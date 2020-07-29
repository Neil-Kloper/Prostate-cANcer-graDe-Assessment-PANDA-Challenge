Directory: ./kaggle contains a kaggle notebook 

	kaggle/Pandas_notebook_with_striplicated_tiles.ipynb 
		Creates tiled images and striplicates them.  It is resource intensive, and takes several hours to create all of the images.

Directory:  ./local contains jupyter notebooks 

	local/cupy-NoLoss-Striplicate_mp.ipynb 
		Creates full size striplicated images.  This is very resource intensive, and it takes a couple of days to create all of the files.

	local/GluePix-twist1.ipynb
		Creates tiled images and striplicates them.  It is resource intensive, and takes several hours to create all of the images.


Note, that my use of cupy in these programs may be buggy, as this is the first time I've used cupy, and it doesn't play well with multiprocessing.


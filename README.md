# Image-classification-Mobilenet
实现了简单的图像分类

Requirement
===
		Python 3.6
		Tensorflow-gpu 1.5.0
		Keras 2.2


The dataset folder structure is as follows:
===
	| - data/
		| - train/
			| - class 0/
				| - image.jpg
					....
			| - class 1/
			  ....
			| - class n/
		| - validation/
			| - class 0/
			| - class 1/
			  ....
			| - class n/

Command
===
 		python train.py --classes num_classes --batch batch_size --epochs epochs --size image_size

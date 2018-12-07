YOLO V2 --PART 1
-----------------
1. openCV installation - check
2. python 3.5 or 3.6
3. Darkflow repo
	https://github.com/thtrieu/darkflow

	build library
	$python setup.py build_ext --inplace
	
4. download the models from repo (YOLO V2 608X608)
	https://pjreddie.com/darknet/yolo/

5. Create a bin folder
	darkflow>bin

6. processing video
	python flow --model cfg/yolo.cfg --load bin/yolo.weights --demo videofile.mp4 --gpu1.0 --saveVideo



YOLO V2 -- PART 2
-------------------
matplotlib

pip install cython numpy
pip install scipy matplotlib
pip install .

pip install numpy scipy matplotlib

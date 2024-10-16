Желательно создать отдельную виртуальную среду для работы с библиотекой OpenCV.

conda create -n "название виртуальной среды"
conda activate "название виртуальной среды"

conda install -c conda-forge notebook
conda install ipykernel
pip install opencv-python

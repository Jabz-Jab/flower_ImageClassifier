# Terminal Instructions
Based on project instructions from Udacity, there are a few specific details about the terminal use that are best to note;

in train.py

In the terminal, train.py is best called with:

```bash
cd python train.py ./flowers -g
```
with cd being the directory in which train.py is in.

with -g representing the GPU connection so that everything runs faster.

with ./flowers being the directory in which we save our training, validation and testing sets. The ./flowers directory would have 3 folders: train, valid, test. These folders would be separated into sub-folders, holding the class number of the flower photos they contain.

in predict.py

In the terminal, predict.py is best called with:
```bash
cd python predict.py ./flowers/test/11/image_03098.jpg ./save_directory/checkpoint.pth -g
```
with cd being the directory in which predict.py is in.

with ./flowers/test/11/image_03098.jpg being the path to the image we'd like to predict.

with ./save_directory/checkpoint.pth being the path to the checkpoint we saved in train.py.

with -g representing the GPU connection so that everything runs faster.

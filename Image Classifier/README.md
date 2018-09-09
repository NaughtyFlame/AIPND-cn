# AI Programming with Python Project

Project code for Udacity's AI Programming with Python Nanodegree program. In this project, students first develop code for an image classifier built with PyTorch, then convert it into a command line application.

# image classifier

## train

```
python3 /home/workspace/paind-project/train.py /home/workspace/aipnd-project/flowers --save_dir /home/workspace/paind-project/checkpoint.pth.tar --arch "vgg19" --learning_rate 0.001 --hidden_units 4096 --epochs 2 --gpu
```

## predict

```
python3 /home/workspace/paind-project/predict.py /home/workspace/aipnd-project/flowers/valid/100/image_07895.jpg /home/workspace/paind-project/checkpoint.pth.tar --top_k 3 --category_names  /home/workspace/aipnd-project/cat_to_name.json --gpu
```
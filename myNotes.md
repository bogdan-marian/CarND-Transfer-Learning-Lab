**download the training data**
```
wget https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5834b432_vgg-100/vgg-100.zip
unzip vgg-100.zip

wget https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5834b634_resnet-100/resnet-100.zip
unzip resnet-100.zip

wget https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5834b498_inception-100/inception-100.zip
unzip inception-100.zip


```

 

**git reminders**
```
git add -u
git commit -m 'just a message'
git push
```
example new file
```
git add myNotes.md
```
In case you are brave
```
git add -A
```

**my results**
```
vgg
Epoch 50/50
 256/4300 
[>.............................] - ETA: 0s - loss: 0.0794 - acc: 1.0003328/4300 
[======================>.......] - ETA: 0s - loss: 0.0803 - acc: 0.9964300/4300 
[==============================] - 0s - loss: 0.0819 - acc: 0.9958 - val_loss: 0.4294 - val_acc: 0.8717

reznet
Epoch 50/50
 256/4300 [>.............................] - ETA: 0s - loss: 0.0319 - acc: 1.0003072/4300 
[====================>.........] - ETA: 0s - loss: 0.0320 - acc: 1.0004300/4300 
[==============================] - 0s - loss: 0.0322 - acc: 1.0000 - val_loss: 0.6154 - val_acc: 0.8079

inceptionV3
Epoch 50/50
 256/4300 
[>.............................] - ETA: 0s - loss: 0.0268 - acc: 1.0002560/4300 
[================>.............] - ETA: 0s - loss: 0.0280 - acc: 1.0004300/4300 
[==============================] - 0s - loss: 0.0274 - acc: 1.0000 - val_loss: 0.8388 - val_acc: 0.7513
```

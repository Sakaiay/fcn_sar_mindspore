## fcn对SAR图像分类(Mindspore)

### train
```
python train.py 
        --data-path="/home/mike/data/AIR-PolSAR-Seg/" 
        --num-classes=5 
        --id=5 
        -b=2
```
`--num-classas`:为分割的种类  
`--id`:为使用GPU的id  
`-b`:batch size

保存的模型在save_weights中
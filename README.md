# NOT ALL PIXELS SINK: PHASE-GUIDED REPRESENTATION LEARNING FOR UNDERWATER IMAGE RESTORATION


# ⚙️ Usage

## Training
You may download the dataset first, and then specify TRAIN_DIR, VAL_DIR and SAVE_DIR in the section TRAINING in `config.yml`.

For single GPU training:
```
python train.py
```

## Inference

Please first specify TRAIN_DIR, VAL_DIR, SAVE_DIR and WEIGHT in section TESTING in `config.yml`.
```
python test.py
```


Pretrained model is available at : [Drive](https://drive.google.com/file/d/1SLyPeFffxh3tmnRMpM-_720t2AJVg_Pn/view?usp=sharing)

Special thanks to the awesome repositories [UIR-Polykernel](https://github.com/CXH-Research/UIR-PolyKernel) and [Phaseformer](https://github.com/Mdraqibkhan/Phaseformer.git), which made this project possible.

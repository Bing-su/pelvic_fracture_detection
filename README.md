# pelvic_fracture_detection

### CLI 커맨드 사용 예제

#### train

```sh
python tools/train.py --config config/fastflow.yaml
```

#### inference

```sh
python tools/inference.py \
    --config config/fastflow.yaml \
    --weight_path results/fastflow/fracture_fastflow/weights/model.ckpt \
    --image_path data/fracture_voucher \
    --save_path results/fastflow/fracture_fastflow/images
```
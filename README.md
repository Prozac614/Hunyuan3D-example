# 1 gpu

‘’‘bash
sglang generate   --model-path tencent/Hunyuan3D-2   --image-path demo.png --save-output --output-path outputs
‘’‘

# tp
‘’‘bash
sglang generate   --model-path tencent/Hunyuan3D-2  --image-path demo.png  --save-output  --output-path outputs --tp-size 2 --num-gpus 2
‘’‘

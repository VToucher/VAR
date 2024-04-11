# VAR

## 1.环境配置
```bash
conda create -n var python=3.9
pip install torch==2.1.0 torchvision==0.16.0 torchaudio==2.1.0 --index-url https://download.pytorch.org/whl/cu118
pip install -U huggingface_hub -i https://pypi.tuna.tsinghua.edu.cn/simple
conda install ipykernel
```

## 2.跑通代码
1. 修改demo_sample.ipynb
    - 在cell中增加代理os.environ['http_proxy']，os.environ['https_proxy']
    - hf_home = 'https://huggingface.co/FoundationVision/var/blob/main'
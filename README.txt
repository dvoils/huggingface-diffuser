python3 -m venv venv
source venv/bin/activate

pip install git+https://github.com/huggingface/diffusers.git#egg=diffusers[training]
pip install accelerate
pip install datasets

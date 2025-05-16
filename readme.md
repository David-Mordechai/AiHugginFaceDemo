## tutorial source
https://www.youtube.com/watch?v=1h6lfzJ0wZw

## Create virtual environment

## Install requirements.txt

## https://huggingface.co/
1. Create account
2. Generate Access Tokens

## To use the Access token run command
huggingface-cli login (right click to paste the key)

## Install Cuda
https://developer.nvidia.com/cuda-downloads

## in virtual enveronment install torch to use cuda (cu128 => this is the version of your cuda)
## to check you'r version after you install cude run in new terminal => nvcc --version
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu128
# Fork

Changes:
- Permissions
- Example Usage   

# Example Usage

    docker run --gpus all --rm -it --ipc=host \
    --name testorch \
    -p 8888:8888 \
    -p 6006:6006 \
    -v $PWD:/workspace \
    putssander/docker-jupyter-pytorch

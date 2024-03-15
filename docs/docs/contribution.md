# Contribute and Develop

## Developer setup

Install via Poetry 1.7.1 and Python3.11 on Ubuntu 22.04
```bash
git clone https://github.com/michaelfeil/infinity
cd infinity
cd libs/infinity_emb
poetry install --extras all --with test
```

To pass the CI:
```bash
cd libs/infinity_emb
make format
make lint
poetry run pytest ./tests
```
as alternative, you may also use:
```bash
cd libs/infinity_emb
make precommit
```

## CLA
All contributions must be made in a way to be compatible with the MIT License of this repo. 
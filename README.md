# Centos7.9에 Python3.9&Package 설치하기

- 미니콘다(Miniconda)에서 Python 3.9 Linux Installer 설치
- 설치 패키지는 requirements.txt 확인

## Excluded(용량 제한으로)
Manually 다운로드 필요
- mkl-2022.1.0-py2.py3-none-manylinux1_x86_64.whl
- opencv_python-4.6.0.66-cp36-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
- PySide2-5.15.2.1-5.15.2-cp35.cp36.cp37.cp38.cp39.cp310-abi3-manylinux1_x86_64.whl
- tensorflow-2.10.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
- torch-1.12.1-cp39-cp39-manylinux1_x86_64.whl

## Install Packages
`pip install --no-index -f ./PKGS/ -r requirements.txt`

FROM pytorch/pytorch:2.7.0-cuda12.6-cudnn9-devel

# 기본 패키지 설치
RUN apt-get update && apt-get install -y \
    python3-pip \
    python3-dev \
    build-essential \
    cmake \
    git \
    curl

# PyTorch, ONNX, 기타 필수 라이브러리 설치
RUN pip3 install --no-cache-dir \
    onnx==1.16.0 \
    onnxruntime==1.18.0 \
    numpy \
    tqdm \
    scipy

# 기본 작업 디렉토리 설정
WORKDIR /workspace

# 컨테이너 기본 실행 명령어
CMD ["bash"]
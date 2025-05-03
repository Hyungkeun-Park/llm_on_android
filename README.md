# llm_on_android

채찍피티와 함께하는 pre-trained LLM 모델 갤럭시에 올려보기 찍먹 프로젝트

## 1. Docker 환경 구성
앞으로의 작업을 위한 가상환경부터 구성하도록 하겠습니다

노트북 cuda version에 맞춰 `2.7.0-cuda12.6-cudnn9-devel`를 base image로 하고\
앞으로의 PTQ 등의 작업에 필요한 라이브러리는 추가적으로 다운받을 수 있게 requirements.txt를 각 폴더 별 구성하였습니다.\


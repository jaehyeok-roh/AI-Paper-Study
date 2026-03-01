# 📄 Vision Transformer (ViT) 논문 리뷰
## 1. 논문 개요
논문 제목: An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale

주요 특징: 자연어 처리(NLP)에서만 쓰이던 Transformer 구조를 컴퓨터 비전(CV) 분야에 최초로 적용하여 혁신적인 성능을 낸 논문.

## 2. 기존 CNN과의 차이점
기존에는 이미지의 특징을 추출하기 위해 합성곱(Convolution) 연산을 주로 사용함.

하지만 ViT는 이미지를 (이곳에 재혁님이 아는 내용을 적어보세요!) 처리함.

## 3. 핵심 구조 (Architecture)
Patch Extraction: 이미지를 16x16 크기의 패치(Patch)로 분할.

Linear Projection: 쪼개진 패치들을 1차원 벡터로 변환.

Positional Embedding: (이곳에 위치 정보가 왜 필요한지 적어보세요!)

Transformer Encoder: Self-Attention 연산을 통해 패치들 간의 연관성을 학습.

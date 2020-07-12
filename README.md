# Free-Form-Image-Inpainting-with-Gated-Convolution
#ICCV 2019 #GAN #Image Inpainting #Computer Vision


# 논문 읽고, 이해,  중

# Introduction
컴퓨터 비전에는 이미지 인 페인팅에 대한 두 가지 광범위한 접근 방식이 있다. 저수준 이미지 피쳐를 사용한 패치 매칭과 딥 컨벌루션을 사용한 피드 포워드 생성 모델이다. 전자의 접근 방식은 그럴듯한 정적인 텍스처를 합성 할 수 있지만 복잡한 장면, 얼굴 및 물체와 같은 정적이지 않은 경우에는 일반적으로 심각한 오류를 만든다. 후자의 접근 방식은 대량의 훈련 세트에서 학습 된 결과를 활용하여 정적이지 않은 이미지의 컨텐츠를 엔드 투 엔드 방식으로 합성할 수 있다. 
# Comparison of different approaches
![Comparison of different approaches](https://user-images.githubusercontent.com/59387983/87162966-a04ce900-c301-11ea-920a-d412c081c615.PNG)

Image Inpainting 분야에서 대표적인 Branches와의 비교

데이터가 가진 정보를 의미적으로 학습이 가능한지

모델이 글로벌한 영역에서의 데이터를 반영하는지

마스크의 형태가 자유로운지

사용자의 가이드 데이터를 반영할 수 있는지

![vanilla convolutions(1)](https://user-images.githubusercontent.com/59387983/87162684-3d5b5200-c301-11ea-9762-7df9f2a54d2b.PNG)
![vanilla convolutions(2)](https://user-images.githubusercontent.com/59387983/87162689-3df3e880-c301-11ea-9b0a-4ea007204f5e.PNG)
![functions of gated convolution](https://user-images.githubusercontent.com/59387983/87162693-3e8c7f00-c301-11ea-8168-56d6bae52cc2.PNG)
![Ilustration of convolutions](https://user-images.githubusercontent.com/59387983/87162695-3f251580-c301-11ea-83bb-f31f2e0759e4.PNG)
![Overview of SN-PatchGAN](https://user-images.githubusercontent.com/59387983/87162699-3f251580-c301-11ea-9975-395880be246a.PNG)
![partial convolution](https://user-images.githubusercontent.com/59387983/87162702-3fbdac00-c301-11ea-96ee-ed95abd7dd47.PNG)



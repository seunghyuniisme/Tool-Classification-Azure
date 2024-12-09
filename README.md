# 공구 분류 모델 프로젝트 (Tool Classification AI Service Using MS Azure Custom Vision)
**Microsoft Azure**의 **Custom Vision(Classification)** 기능을 활용하여 다양한 공구 이미지를 분류하고 학습하는 AI 모델을 만들었습니다. 학습된 모델은 API 형태로 제공되며, **HTML**, **CSS**, **JavaScript**를 사용하여 웹 애플리케이션으로 구현하였습니다. 사용자가 웹 페이지에서 공구 이미지를 업로드하면, 모델이 이를 자동으로 분류하여 해당 공구의 정보(이름, 종류, 가격 등)를 알려줍니다.  


This project utilizes **Microsoft Azure's Custom Vision (Classification)** feature to create an AI model that classifies and learns from various tool images. The trained model is provided as an API and has been implemented as a web application using **HTML**, **CSS**, and **JavaScript**. When users upload tool images on the web page, the model automatically classifies the tools and provides information such as the tool’s name, type, and price.


# 프로젝트의 목표 및 필요성 (Project Goal and Necessity)
* 카탈로그 제작 효율성 증대 (Enhancing the Efficiency of Catalog Production)
* 온라인 상품 등록의 자동화 (Automating Online Product Registration)
* 비숙련자 지원을 통한 생산성 향상 (Improving Productivity by Supporting Non-Experts)



## 주요 기능
1. **공구 이미지 분류**  
   - MS Azure Custom Vision 모델을 활용해 업로드된 공구 이미지를 분석하고, 해당 공구의 이름(종류) 및 분류를 제공합니다.

2. **공구 정보 제공**  
   - 공구의 이름, 가격, 제품 코드, 수량 등 다양한 정보를 제공합니다.

3. **판매 사이트 업로드 기능 (추후 추가 가능)**  
   - 분류된 공구 정보를 사용자가 바로 판매 사이트에 업로드할 수 있는 기능이 추가될 예정입니다.


## 사용된 기술
- **MS Azure Custom Vision API**
- **HTML, CSS**
- **Django Framework**


## 사용 방법
1. Visual Studio Code에서 `web` 폴더에 있는 `main.html` 파일을 열어 실행합니다.
2. 웹 페이지가 로드되면 "시작하기" 버튼을 클릭하고 아래 순서대로 진행:
   - 공구 이미지 업로드
   - 분류 결과에 따라 이미지 재업로드 또는 가져가기 버튼 클릭
   - (추후 추가 기능) 공구명, 가격, 제품 코드, 수량 등을 판매 사이트에 업로드


## 실행 화면
![main](https://github.com/user-attachments/assets/f4437aa8-2266-443e-bc68-5d3676bfbee2)
![image_upload](https://github.com/user-attachments/assets/5298b76e-a9e6-4345-8395-e36df699df52)



## 사용법
이 프로젝트는 Azure AI 서비스를 사용하므로, **API 키와 엔드포인트**가 필요합니다. 
Azure Portal에서 해당 정보를 얻을 수 있습니다.

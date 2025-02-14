# 공구 분류 서비스 (Tool Classification Service Using Microsoft Azure AI)
**Microsoft Azure의 Azure AI Custom Vision를 사용하여 다양한 공구 이미지를 학습 및 분류하고 해당 모델을 통해 공구 분류 웹 서비스를 개발하였습니다.**   

학습된 모델은 API 형태로 제공되며, **Python**, **HTML**, **JavaScript**, **Django Framework** 등을 사용하여 웹 페이지 형태로 구현하였습니다. 사용자가 웹 페이지에서 공구 이미지를 업로드하면, 모델이 이를 자동으로 분류하여 해당 공구의 종류, 이름, 가격 등의 정보를 알려주는 서비스입니다.           


***


**A web service for tool classification is created using Microsoft Azure Custom Vision to train and classify various tool images.**   

The trained model is provided as an API and implemented as a web application using **Python, HTML, JavaScript, and the Django Framework**. When users upload a tool image on the web page, the model automatically classifies the tool and provides information such as its type, name, and price.  





## :pushpin: 프로젝트의 목표 및 필요성 (Project Goal & Necessity)

* 카탈로그 제작 효율성 증대 (Enhancing the Efficiency of Catalog Production)
* 온라인 상품 등록의 자동화 (Automating Online Product Registration)
* 비숙련자 지원을 통한 생산성 향상 (Improving Productivity by Supporting Non-Experts)    


## :pushpin: 주요 기능 (Key Features)

1. **공구 이미지 분류 (Tool Image Classification)**  
   MS Azure Custom Vision 모델을 활용해 업로드된 공구 이미지를 분석하고, 해당 공구의 이름(종류) 및 분류를 제공합니다.

2. **공구 정보 제공 (Tool Information Display)**  
   공구의 이름, 가격, 제품 코드, 수량 등 다양한 정보를 제공합니다.

3. **판매 사이트 업로드 기능 (추후 추가 가능) Sales Site Upload Feature**  
   분류된 공구 정보를 사용자가 바로 판매 사이트에 업로드할 수 있는 기능이 추가될 예정입니다.
    

## :pushpin: 활용 기술 (Tech)

- MS Azure Custom Vision
- Jupyter Notebook
- Python
- HTML, CSS, JS
- Django Framework


## :pushpin: 사용 방법 (How to Use)

1. Visual Studio Code에서 `web` 폴더에 있는 `main.html` 파일을 열어 실행합니다.
2. 웹 페이지가 로드되면 "시작하기" 버튼을 클릭하고 아래 순서로 진행합니다.
   - 공구 이미지 업로드
   - 분류 결과에 따라 이미지 재업로드 또는 가져가기 버튼 클릭
   - (추후 추가 기능) 공구명, 가격, 제품 코드, 수량 등을 판매 사이트에 업로드


-   Open the `main.html` file located in the `web` folder using **Visual Studio Code** and run it.
-   Once the web page loads, click the **"Start"** button and follow these steps:
    -   Upload a tool image.
    -   Based on the classification results, click either the **Re-upload** or **Retrieve** button.
    -   (Future Update) Upload the tool’s name, price, product code, and quantity to a sales platform.
      


## :pushpin: 실행 화면 (Result)
![main](https://github.com/user-attachments/assets/f4437aa8-2266-443e-bc68-5d3676bfbee2)
![image_upload](https://github.com/user-attachments/assets/5298b76e-a9e6-4345-8395-e36df699df52)
![image_upload](https://github.com/user-attachments/assets/51fc3b66-0678-4e9e-8cd9-abc359c14489)  


  

## :pushpin: 참고 사항 (Notes)
이 프로젝트는 Azure Custom Vision 서비스를 사용하므로, 모델에 접근하기 위한 API 키와 엔드포인트가 필요합니다.  
해당 정보는 Azure Portal에서 얻을 수 있습니다.

This project uses the Azure Custom Vision service, so you'll need the API key and endpoint to access the model.  
These details can be obtained from the Azure Portal.


<div align="center">

![logo](https://github.com/CurrencySense/.github/blob/main/profile/Slide%2016_9%20-%201.png)

</div>

# Currency Sense
**Currency Sense: Financial Clarity At Your Fingertips**, Is an application developed to assist visually impaired people in identifying the value of money, by scanning the money. In addition, the application is made with a friendly UI design for the visually impaired. The application has a voice output that will notify you of the scan results, and a navigation location that can be used. 

## Organization
<div align=center>

| NAME | LEARNING PATH |
|:--------------------:|:--------: |
| Chiquito Shaduq Aurick Fulvian |`Machine Learning`|
| Putri Rigita Cahyani |`Machine Learning`|
| Syifa'Ul Aini Zahroh |`Machine Learning`|
| Annadia Dwina Haqiqi |`Cloud Computing`|
| Muhammad Dafin Abiyasa |`Cloud Computing`|
| Devin Alfanius |`Mobile Development`|
| Riski Agung Romadhon |`Mobile Development`|

</div>

### Job Desk
- ML<br>
The Machine Learning Division works in the preparation and delivery of models that will be used in the classification of money values. The initial preparation of this division is to conduct research related to the nominal currency that is quite widely circulated in the community, then collect data samples or can be said to be a model and continued by training the model by dividing it into 2 parts, namely Training and Testing, then validating by recognizing the nominal money given.<br>
Tools: Tensorflow, Python, and Library Python

- CC <br>
The CC division is responsible for deploying the model to the cloud and then creating an API so that the model can be accessed online. After the API is complete, they will provide the API to the MD team in the form of an endpoint, which makes it easy for the MD division to make "requests" to the cloud. Such as: accessing the model in the cloud when the user is using the internet. <br>
Tools: Google Cloud Platform

- MD <br>
MD Division, this division is responsible for making android applications, such as designing application workflows, application designs, features that will be useful for users. This division also designs how the application can run well, especially ease and comfort for users. On-device and cloud model implementation is also the responsibility of this division. <br>
Tools: Android Studio, Tensorflow Lite, Android Jetpack, Material3 Design

## Program Flow
```mermaid
graph
  A(Splash)-->B(Main Activity);
  B-->C(Scan Activity);
  B-->D(History Activity);
  C-->E(Camera Activiy);
  E-->F(Result Activity);
  D-->G(History Item Activity);
```

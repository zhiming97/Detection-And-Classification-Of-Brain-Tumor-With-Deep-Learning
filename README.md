

  

## <p> Detection And Classification Of Brain Tumor With Deep Learning</p>

<!-- PROJECT LOGO -->

<div align="left">
  <a href="">
    <img src="https://media.istockphoto.com/id/1311310663/vector/diagnostic-checkup-of-brain-health-by-doctor-doctors-doing-medical-research-examination.jpg?s=612x612&w=0&k=20&c=j7k0TqtM7X2iTC12ijcVophfTuFwRHiyoIgAo59gi04=" alt="Logo" width="700" height="500">
  </a>
  </div>
  
  
  <br />
  <p align="left">
    <br />
   
  





<!-- ABOUT THE PROJECT -->
## About The Project
                 
<div align="">
  <a href="">
    <img src="https://healthitanalytics.com/images/site/article_headers/_normal/ThinkstockPhotos-495951912.jpg" alt="Logo" width="500" height="250">
  </a>

<br />
  <br />
<p align="justify">
This project attempts to develop a deep learning-based detection and classification model to detect and classify the different types of brain tumors.


## Project Motivation 
- Currently, a Magnetic Resonance Imaging (MRI) screening is the best way to detect brain tumours. 
- Due to the to the level of complexities involved in brain tumours and their properties, the identification of the type of brain tumours are complicated to begin with. 
- Hence, a thorough analysis by professionals on the MRI images is required to determine whether the tumours are either malignant or benign.
- Occasionally, these manual examinations could be prone to error and bias as different professionals have different point of view based on their own experiences.
- Lack of medical professionals in developing countries makes it difficult and time-consuming to determine the properties of the brain tumour based on the MRI screening. 
- An automated brain tumour detection and classification system can be developed using deep learning algorithms such as Convolution Neural Network (CNN) to assist medical practitioners in their brain tumour diagnosis and treatment plans.

## Built With
<div align="">
  <a href="">
    <img src="https://www.devopsschool.com/blog/wp-content/uploads/2022/03/Python-01-2.png" alt="Logo" width="100" height="60">
  </a>
  
## Dataset 
  
### As shown below is a table summary of the dataset 
  
<img width="656" alt="image" src="https://user-images.githubusercontent.com/97498951/211266845-7b44bab9-c3ae-4400-8364-3f45b7675f74.png">

- The dataset used in this assignment is a combination of a few publicly available brain MRI images dataset. 
- It is obtained from Kaggle and the URL to download the dataset is https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset. 
- However, in this assignment, the dataset will be divided manually into training and testing at a ratio of 80:20 because all the images will be combined into a single list when they are imported from google drive. 



## Results
<img width="849" alt="image" src="https://user-images.githubusercontent.com/97498951/211269261-69018998-0827-4589-b6f6-2d1e8dd33680.png">

- The baseline variant of EfficientNet (B0) and without any tuning performed on it, the model is able to achieve an astonishing testing accuracy of 94.52%. 
- The different hyperparameters tuned in Model 2 are increasing the number of training epochs, implementing decaying learning rate and increasing the batch size. 
- Although the training process of Model 2 took longer than Model 1, it is still considered to be worth it as there is a slight increase of around 5 % in the testing accuracy. 
- This 5% increment may not seem very significant on paper, but when comparing it to the number of human lives it can save, this 5% increment suddenly becomes very significant.

## Future Recommendations
- Experimentation is everything in deep learning as the results may vary with different hyperparameter values and the type of CNN architecture used.
- The performance of Model 2 (tuned model) is very much likely to improve by using other state of the art versions of EfficientNet e.g. B1 – B7.
- To train Model 2 with different medical datasets as different datasets may introduce different challenges.

## ************** Click [here] to read the full report ******************

</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[here]: https://1000logos.net/wp-content/uploads/2020/08/Python-Logo.jpg

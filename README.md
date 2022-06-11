# Your Pet Care

Your Pet Care is an android based application that serves all needs related to all pets like dogs and cats it has pet shop features that can be bought online, pet detection, vet consultation, and many more.

<div style="text-align: center;"><img src="https://drive.google.com/uc?export=view&id=1CmBzLhC8ljjB2jcjmYOb2vUIMDb2SQEA"/></div>

# Project Structures

📦yourpetcare-ml
┣ 📂sample_images
┃ ┣ 📜test1.jpg
┃ ┣ 📜test2.jpg
┃ ┣ 📜test3.jpg
┃ ┣ 📜test4.jpg
┃ ┣ 📜test5.jpg
┃ ┣ 📜test6.jpg
┃ ┣ 📜test7.jpg
┃ ┗ 📜test8.jpg
┣ 📂saved_model
┃ ┣ 📂assets
┃ ┣ 📂variables
┃ ┃ ┣ 📜variables.data-00000-of-00001
┃ ┃ ┗ 📜variables.index
┃ ┣ 📜keras_metadata.pb
┃ ┗ 📜saved_model.pb
┣ 📂tensorflow_lite
┃ ┣ 📜resnet50_ypc_fp32.tflite
┃ ┗ 📜tflite_ypc.ipynb
┣ 📜.gitattributes
┣ 📜.gitignore
┣ 📜labels.txt
┣ 📜README.md
┗ 📜Your_Pet_Care.ipynb

# Machine Learning

We will use the **Oxford-IIIT Pet Dataset** from [https://www.robots.ox.ac.uk/~vgg/data/pets/](https://www.robots.ox.ac.uk/~vgg/data/pets/) which contains 37 labels out of 7349 total images. Then we will prepare the data using the **TensorFlow Dataset** and then do **Image Augmentation**. For the model, we will use our **CNN model**. But if analyzing and comparing the results from the model we created is not good enough, we will use **Transfer Learning**. Finally, we will convert the model we created into **TensorFlow Lite** to be used as an Android Application and **TensorFlow JS** to be used as API.

## Build the Model

| Model        | Accuracy | Val Accuracy |
| ------------ | -------- | ------------ |
| Our CNN      | 0.3246   | 0.2433       |
| Inception V3 | 0.9571   | 0.8661       |
| Resnet50     | 0.9516   | 0.9185       |

Although the approach of each model is different, but from our perspectives and observations we can conclude that we use the resnet50 model for our project use case.

# Project Members

- (ML) M2281G2425 - Dimas Rumekso Putra - Universitas Negeri Medan
- (ML) M2015G1410 - Futura Milyana Syauqiya Salsabila - Universitas Negeri Yogyakarta
- (ML) M2393F2954 - Muhamad Azizi - Universitas Serang Raya
- (MD) A2183G1775 - Firman Diatullah Guna Darma - Universitas Amikom Yogyakarta
- (MD) A2267F2297 - Putik Aulia Safitri - Universitas Muhammadiyah Sukabumi
- (CC) C2006F0471 - Pradipa Aisyah Tri Syakina - Universitas Brawijaya

# Project Repos

- [Machine Learning](https://github.com/memelabela/yourpetcare-ml)
- [Mobile Development](https://github.com/vandarma27/yourpetcare-md)
- [Cloud Computing](https://github.com/pradipaaisyah/yourpetcare-cc)

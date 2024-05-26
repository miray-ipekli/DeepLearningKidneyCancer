# Kindey Cancer Deep Learning Model

## Proje Açıklaması

Bu projenin temel amacı, böbrek kanseri tanısı için görüntü sınıflandırma yapmaktır. Projede kullanılacak veri seti, normal ve tümörlü böbrek görüntülerini içermektedir. Toplamda 10,000 adet görüntü içeren bu veri seti üzerinde bir derin öğrenme modeli oluşturulacak ve böbrek kanseri teşhisinde etkili bir sınıflandırma modeli geliştirilecektir.

Veri setindeki normal ve tümörlü böbrek görüntülerinin detaylı bir incelemesi yapılarak veri seti; eğitim, test ve doğrulama seti olarak bölünmüştür. Veri ön işleme adımında, görüntülerin özellikleri standartlaştırılmıştır. Model, eğitim seti üzerinde eğitilmiş, eğitim süreci izlenerek doğrulama seti üzerinde performans değerlendirilmiş ve overfitting'i önlemek adına dropout ve batch normalization ve early stopping gibi teknikler kullanılmıştır. Son olarak, modelin test seti üzerindeki performansı hassasiyet, duyarlılık, doğruluk ve f1 score gibi sınıflandırma metrikleriyle değerlendirilmiş ve elde edilen sonuçlar raporlanarak böbrek kanseri tanısı üzerindeki uygulamalar değerlendirilmiştir.


---

## Proje Dosya Yapısı

- **/Deep Learning**
  - **/ANN**
    - `ANN_1_Eğitim.ipynb`
    - `ANN_2_Eğitim.ipynb`
  - **/CNN**
    - `CNN_1_Eğitim.ipynb`
    - `CNN_2_Eğitim.ipynb`
  - **/Transfer Learning**
    - `TransferLearning.ipynb`
    - `TransferLearning_2.ipynb`
- `README.md`


---

## Kurulum

- **1.	Python Yüklemesi:**
  - Python'un resmi web sitesinden 3.0 sürümünü indirip yükleyin. Yükleme sırasında "PATH'e ekle" seçeneğini işaretleyerek Python'ı sistem yoluna ekleyin.

- **2.	Gerekli Kütüphanelerin Yüklenmesi:**
  - Terminal veya komut istemcisinde projenizin bulunduğu dizine gidin ve aşağıdaki komutu kullanarak gerekli kütüphaneleri yükleyin:
  ```pip install numpy pandas matplotlib opencv-python scikit-learn tensorflow keras-tuner seaborn glob os cv2```

- **3.	Veri Seti:**
   -  **Veri Seti Link :** [Veri Seti](https://drive.google.com/file/d/1-ukgRGfCDrCYXVU4HiU9gQdXdBVko9S4/view )
---

## Proje Model Linkleri

- **CNN-1 Link :** [CNN-1](https://colab.research.google.com/drive/1cShrIANAewj10l5_6i3mrKl8ls_mWCQT?usp=sharing)
- **CNN-2 Link :** [CNN-2](https://colab.research.google.com/drive/1NolI6x2DsRA4Qy60Qr7Z_EdBH-NkT08U?usp=sharing)
  
<br> 

- **Transfer Learning-1 Link :** [Transfer Learning-1](https://colab.research.google.com/drive/133OqsvSOfk4aHDLxL9dRMQewckVfUI37?usp=sharing)
- **Transfer Learning-2 Link :** [Transfer Learning-2](https://colab.research.google.com/drive/16XO-lDVrCd_dqbgH44AMBOWsBT4KKPmM?usp=sharing)
  
<br> 

- **ANN-1 Link :** [ANN-1](https://colab.research.google.com/drive/1xj62iZZVT33vNg4sqo1cAMN7VucuBSEV?usp=sharing)
- **ANN-2 Link :** [ANN-2](https://colab.research.google.com/drive/1RA9M4_OuzVPTufUf4mBT6oZFVkXSM5Oo?usp=sharing)

---

## Katkılar

### Projeyi yaparken bunlardan yararlandık;

[Fatih Bal Github](https://github.com/balfatih)

[Keras documentation: Keras 3 API documentation](https://keras.io/api/)

[Hiperparametre Optimizasyonu](https://medium.com/bilişim-hareketi/hiperparametre-optimizasyonu-9ba0e7f32e6f)

[Öğrenme Aktarımı/Transfer Learning ](https://medium.com/novaresearchlab/öğrenme-aktarımı-transfer-learning-c0b8126965c4)

[How to Avoid Overfitting in Deep Learning Neural Networks](https://machinelearningmastery.com/introduction-to-regularization-to-reduce-overfitting-and-improve-generalization-error/)

[Evrişimsel Sinir Ağında Niçin Dropout Kullanmamalısınız](https://medium.com/@tuncerergin/evrisimsel-sinir-aginda-nicin-dropout-kullanmamalisiniz-7e31941f8bb0) 

[How to NOT overfit in Deep Learning ](https://dev.to/tecnosam/how-to-not-overfit-in-deep-learning-69a)

[Easy Hyperparameter Tuning with Keras Tuner and TensorFlow ](https://pyimagesearch.com/2021/06/07/easy-hyperparameter-tuning-with-keras-tuner-and-tensorflow/)

[What is Transfer Learning? ](https://www.geeksforgeeks.org/ml-introduction-to-transfer-learning/)

[tf.keras.optimizers.legacy.Adam](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/legacy/Adam)

[How To Create a Neural Network In Python – With And Without Keras](https://www.activestate.com/resources/quick-reads/how-to-create-a-neural-network-in-python-with-and-without-keras/)

[Transfer Learning using CNN (VGG16)](https://www.turing.com/kb/transfer-learning-using-cnn-vgg16)


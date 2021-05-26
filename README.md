# CNN-ile-Nesne-Siniflandirma
CNN-Keras
## Cnn Nedir?
## Tensorflow Nedir?
## Keras Nedir?
### Keras Projesi Nasıl Oluşturulur?
* Anaconda Promt açılır.
* Yeni bir çalışma alanı oluşturulur.
```
conda create --name proje_adi
```

* Oluşturulan çalışma alanı aktif hale getirilir.
```
activate proje_adi
```

* Tensorflow yüklenir.
```
conda install Tensorflow
```

* Keras yüklenir
```
conda install Keras
```

* Ve çalışma alanı artık hazır. Anacondaya gidip yüklü ortamlardan çalışma alanımızı görüntüleyebiliriz.
* Applications on kısmından çalışma alanımızı açabiliriz.
* Projemize tıklayıp alt kısımda çıkan uygulamalardan birini seçerek çalışmaya başlayabilirsiniz.
* Biz Jupyter notebook ile devam edeceğiz.
* Veri seti import edilir.
```
from keras.datasets import veriseti
```

* Veri seti eğitim ve test olarak ikiye ayrılır.
```
(x_train,t_train), (x_test,y_test) = veriseti.load_data()
```

* Numpy kütüphanesi import edilir.
```
import numpy as np
```





##

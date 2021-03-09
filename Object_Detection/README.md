# tflite_avto_num_recognation
Определение положнеия номера мшины

Этот проект демонстрирует  как использовать TensorFlow2 и Keras для до обучения  нейронной сети  определения положения номера.
В качестве данных для тренировки использован  набор данных о парковке в китайском городе CCPD (https://github.com/detectRecog/CCPD). Скачать https://drive.google.com/file/d/1m8w1kFxnCEiqz_-t2vTcgrgqNIv986PR/view?usp=sharing. Конвертирование его в xml: ccpd2020_name_to_xml.ipynb.А так же 600 фографий из набора https://yadi.sk/d/EAfnQ947criHW

Обучение было выполнено в https://github.com/tensorflow/models по инструкции https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html
Для тренировки была выбрана модель http://download.tensorflow.org/models/object_detection/tf2/20200711/ssd_resnet50_v1_fpn_1024x1024_coco17_tpu-8.tar.gz
Для сохранение модели была использована программа https://github.com/tensorflow/models/blob/master/research/object_detection/export_tflite_graph_tf2.py 
  
добавлена работа с  TensorFlow Lite.


![пример работы](https://github.com/sovse/tflite_avto_num_recognation/blob/main/img/777.png?raw=true)



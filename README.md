# NeuralStyleTransfer
Rete Neurale (allenata con Tensorflow) per generare - a partire da una immagine - una sua nuova versione modificata in base ad uno stile predefinito (ad esempio il quadro di Marylin Monroe di Andy Warhol, un dipinto di Van Gogh, etc.)

eseguire il file python per il training del modello e la generazione dell'immagine su un computer dotato almeno di una GPU Nvidia GTX 1060 (altrimenti il processo gestito da un processore CPU impiega troppo tempo)

necessita del modello pre-trained VERY DEEP CONVOLUTIONAL NETWORKS FOR LARGE SCALE IMAGE RECOGNITION (vgg19_weights_tf_dim_ordering_tf_kernels_notop.h5)
https://www.kaggle.com/keras/vgg19/home?select=vgg19_weights_tf_dim_ordering_tf_kernels_notop.h5 (file da 80Mb)

Articolo su @TDataScience
https://towardsdatascience.com/neural-style-transfer-series-part-2-91baad306b24

Codice @Github
https://github.com/Shashi456/Neural-Style/blob/master/Neural%20Style%20Transfer/train_TensorFlow.py

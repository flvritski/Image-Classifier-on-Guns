# Image Classifier on Guns
Classifying Pistols, Revolvers and Rifles using **_Transfer Learning_**

Repo developed using this [CodeLab](<https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/?utm_campaign=chrome_series_machinelearning_063016&utm_source=gdev&utm_medium=yt-desc#0>) by Google as a guide.

It is one easy technique and it can be used in Police Enforcement to detect the weapon of the shooter.

## Result ##
> (base) Stefans-MacBook-Pro:tensorflow-for-poets-2 stefanflorin$ python -m scripts.label_image \
> --graph=tf_files/retrained_graph.pb \
> --image=tf_files/flower_photos/Rifles/193px_Safir_T_17.jpg
> 2019-06-15 01:16:59.238671: I tensorflow/core/platform/cpu_feature_guard.cc:141] Your CPU supports instructions that this > > TensorFlow binary was not compiled to use: AVX2 FMA

> Evaluation time (1-image): 0.261s

> **rifles (score=0.99452)**
> pistol (score=0.00547)
> revolver (score=0.00001)

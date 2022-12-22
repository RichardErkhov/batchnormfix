# batchnormfix
tensorflow-directml user and tired of `DML doesn't support exponential_avg_factor != 1 at the moment` ? 
you can use batchnormfix - another level of "temporary solution than needs to be fixed and never be pushed in production"

just do `from batchnormfix import BatchNormalization_fixed`
and change `tf.keras.layers.BatchNormalization()` to `BatchNormalization_fixed`

p.s. if any issues, I dont hold liability, but still you can write to issues and I try to make "temporary solution" for your problem =)

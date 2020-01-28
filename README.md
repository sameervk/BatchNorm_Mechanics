Mechanics of Batch Normalization
================================
To understand how batch normalization is performed, I have carried out step-by-step process, and explained with decently sufficient comments, of performing batch normalization on simple input in tensorflow (2.1).

Paper: Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift

		Sergey Ioffe, Christian Szegedy

		https://arxiv.org/abs/1502.03167

1. Writing custom layers in tf.keras for batch normalization 
2. Using tf.nn.batchnormalization function and comparing the results with custom-defined functions in tf to carry out the same
3. Currently, examining the same Keras layer for deeper understanding.

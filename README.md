[Ecole Polytechnique Fédérale de Lausanne (EPFL)]: https://www.epfl.ch/
[Signal Processing Laboratory (LTS5)]: https://lts5www.epfl.ch
[IEEE International Conference on Image Processing (ICIP 2017)]: http://2017.ieeeicip.org/
[paper]: https://infoscience.epfl.ch/record/225655
[TensorFlow]: (https://www.tensorflow.org)

# LEFISTA: Learned Extended Fast Iterative Shrinkage-Thresholding Algorithm

## Associated publication

### Learning the weight matrix for sparsity averaging in compressive imaging

Dimitris Perdios<sup>1</sup>, Adrien Besson<sup>1</sup>, Philippe Rossinelli<sup>1</sup>, and Jean-Philippe Thiran<sup>1, 2</sup>

<sup>1</sup>[Signal Processing Laboratory (LTS5)], [Ecole Polytechnique Fédérale de Lausanne (EPFL)], Switzerland

<sup>2</sup>Department of Radiology, University Hospital Center (CHUV) and University of Lausanne (UNIL), Switzerland

[Paper] accepted to the [IEEE International Conference on Image Processing (ICIP 2017)].

> We propose to map the fast iterative shrinkage-thresholding algorithm (FISTA) to a deep neural network (DNN), with a sparsity prior in a concatenation of wavelet bases, in the context of compressive imaging.
> We exploit the DNN architecture to learn the optimal weight matrix of the corresponding reweighted l<sub>1</sub>-minimization problem.
> We later use the learned weight matrix for the image reconstruction process, which is recast as a simple l<sub>1</sub>-minimization problem.
> The approach, denoted as **learned extended FISTA (LEFISTA)**, shows promising results in terms of image quality, compared to state-of-the art algorithms, and significantly reduces the reconstruction time required to solve the reweighted l<sub>1</sub>-minimization problem.

#### [Paper] history:
* v1: submitted preprint
* v2: accepted preprint
* v3: fix typos and few values in table 1, update table 1 layout

## Code
The code to reproduce the results will be available very soon (most probably during the last week of September).
If you want to be notified, you can write me an [email](mailto:dimitris.perdios@epfl.ch).
Sorry for the inconvenience.

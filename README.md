# COVID19-data-classification-using-BayesCNN-with-variational-inference

Grand challange link: https://covid-ct.grand-challenge.org/

Dataset is already uploaded with code.

Dataset link: https://github.com/UCSD-AI4H/COVID-CT

Our implementation is based on [this paper](https://arxiv.org/abs/1901.02731).

### Layer type

* **BBB_LRT (Bayes by Backprop w/ Local Reparametrization Trick):**  
  This layer combines Bayes by Backprop with local reparametrization trick from [this paper](https://arxiv.org/abs/1506.02557). 
  This trick makes it possible to directly sample from the distribution over activations.
  
 

# Grad-Work
Grad Work of Rong Ma

x: the feature vectors of the labeled training instances  
  pickle(scipy.sparse.csr_matrix)
  construct with csc_matrix(D)
y: the one-hot labels of the labeled training instances
  pickle(numpy.ndarray)
  construct with normal array
allx: the feature vectors of both labeled and unlabeled training instances (a superset of `x`)
  same with x
ally: we do not have ally here?
graph: a `dict` in the format `{index: [index_of_neighbor_nodes]}.
  pickle(collections.defaultdict)
  
tx: the 

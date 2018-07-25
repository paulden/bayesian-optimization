# Bayesian Optimization applied to database tuning

This repository holds a [notebook](https://github.com/paulden/bayesian-optimization/blob/master/bayesian_optimization.ipynb) to explain how Bayesian optimization can be used on a concrete case to fine-tune a database configuration.

A secondary [notebook](https://github.com/paulden/bayesian-optimization/blob/master/bayesian_optimization_complex.ipynb) has been added with a more complex use case to visualize how Bayesian optimization may also be used with non-elementary behaviors.

To run the notebooks by yourself, be sure to use a Jupyter kernel with the required packages (see `requirements.txt`).

## References

- D. Van Aken, A. Pavlo, G. J. Gordon, B. Zhang, *Automatic Database Management System Tuning Through Large-scale Machine Learning*, 2017 - [Paper](https://db.cs.cmu.edu/papers/2017/p1009-van-aken.pdf) - [Repo](https://github.com/cmu-db/ottertune) : Original idea
- S. Duan, V. Thummala, S. Babu - *Tuning Database Configuration Parameters with iTuned*, 2009 - [Paper](https://users.cs.duke.edu/~shivnath/papers/ituned.pdf) : Original idea
- Scikit-Optimize [repository](https://github.com/scikit-optimize/scikit-optimize) : Great package and documentation

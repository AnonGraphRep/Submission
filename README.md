# Submission
The code seen here is a Jupyter notebook for a module's coursework. It was developed on a google colab instance with pytorch 1.13.0+cu116.

# Word of warning
Because weight matrices could not be shared across m values (as the learned distributions needed to be different, and this better replicated conditions from models trained for real-world tasks), the batching really isn't great. In other words: this trains slowly - I had it on in the background for a couple hours, even with CUDA support.

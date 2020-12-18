# DeepFlag: The Deep Learning Flag Generator
This project uses StyleGAN2-ADA to generate new flags based on 1300 flags from nation-states, municipalities, organizations, and custom-made flags. DeepFlag aims to help citizens and organizations in the difficult process of designing new flags (e.g. [2015-2016 New Zealand flag referendums](https://en.wikipedia.org/wiki/2015%E2%80%932016_New_Zealand_flag_referendums))

StyleGAN2-ADA is the latest iteration of [Generative-Adversarial Networks](https://en.wikipedia.org/wiki/Generative_adversarial_network) (GANs) developed by NVIDIA. GANs are neural-network based algorithms that allows the generation of images or videos from training data, and are commonly known for their use in [DeepFakes](https://en.wikipedia.org/wiki/Deepfake).

# Organization of Repository
1. The [code_notebooks](https://github.com/jcpark376/deepflag/tree/main/code_notebooks) folder contains three files.
    * [resize](https://github.com/jcpark376/deepflag/blob/main/code_notebooks/resize.ipynb): resizing and formatting image files to be fed into neural network.
    * [training](https://github.com/jcpark376/deepflag/blob/main/code_notebooks/Main%20Stylegan2-ada%20Custom%20Training.ipynb): training of the neural network
    * [generation](https://github.com/jcpark376/deepflag/blob/main/code_notebooks/Generator.ipynb): generation of newly generated flags
2. [PDF of Presentation](https://github.com/jcpark376/deepflag/blob/main/presentation/Presentation.pdf) based on this project.
3. [Example images folder](https://github.com/jcpark376/deepflag/tree/main/example_generated)

# Select Generated Flags 
![Example4](https://github.com/jcpark376/deepflag/blob/main/example_generated/Exampleof4.jpg)
(more flags in the [Example images folder](https://github.com/jcpark376/deepflag/tree/main/example_generated))

# Acknowledgements
* This project utilized [Google Colaboratory](colab.research.google.com) for training and generation of the neural network
* NVIDIA's [repo for StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada)
* Tutorials and notebooks on StyleGAN2-ADA by [Derrick Schultz](https://www.youtube.com/channel/UCaZuPdmZ380SFUMKHVsv_AA)
* [Chris Doenlen](https://github.com/scrapfishies) for his help and knowledge with GANs.

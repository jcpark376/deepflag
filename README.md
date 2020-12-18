# DeepFlag: The Deep Learning Flag Generator
This project uses StyleGAN2-ADA to generate new flags based on 1300 flags from nation-states, municipalities, organizations, and custom-made flags. DeepFlag aims to help citizens and organizations in the difficult process of designing new flags (e.g. [2015-2016 New Zealand flag referendums](https://en.wikipedia.org/wiki/2015%E2%80%932016_New_Zealand_flag_referendums))

StyleGAN2-ADA is the latest iteration of [Generative-Adversarial Networks](https://en.wikipedia.org/wiki/Generative_adversarial_network) (GANs) developed by NVIDIA. GANs are neural-network based algorithms that allows the generation of images or videos from training data, and are commonly known for their use in [DeepFakes](https://en.wikipedia.org/wiki/Deepfake).

# Organization of Repository
1. The [code_notebooks](https://github.com/jcpark376/deepflag/tree/main/code_notebooks) folder contains three files.
    * [resize](): resizing and formatting image files to be fed into neural network.
    * [training](): training of the neural network
    * [generation](): generation of newly generated flags
2. [PDF of Presentation]() based on this project.

# Acknowledgements
* NVIDIA's [repo for StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada)
* Tutorials and notebooks on StyleGAN2-ADA (by [Derrick Schultz](https://www.youtube.com/channel/UCaZuPdmZ380SFUMKHVsv_AA), from Artificial Images)
* [Chris Doenlen](https://github.com/scrapfishies), data scientist, for his help and knowledge with GANs.


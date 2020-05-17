# MRUNet-Masking
An experimental implementation of MultiRes-U-Net for facial feature segmentation using the CelebAMaskHQ dataset.

The aim is to utilise and discover the compatibility provided by
MultiResUNet models, originally utilised for Medical Image segmentation, and check the
feasibility of utilising the aforementioned method in order to provide segmentation of facial
features (lips and eyes in our case).

**Refer the [pdf](https://github.com/AbhishekSinghDhadwal/MRUNet-Masking/blob/master/Investigative%20Report%20on%20the%20compatibility%20of%20MultiResUNet%20for%20facial%20segmentation.pdf) for further details on the documentation, code implemented and directions to follow before running the notebooks.**

**NOTE**: The original implementation was created on **Google Colab**, and can be tested [here](https://colab.research.google.com/drive/10Vb4Ukv4xOG35bS1sUAVp2j2YA2L1xjZ) with the sample implementations provided. I would recommend colab for viewing and using these notebooks for any and all purposes as many "improvements" are made in order to compensate for restraints pertaining to both Google Drive and Google Colab (eg. The workaround notebooks for time and RAM restraints in the /WorkAroundNB section of this repo) which are visible in the notebook code and comments.

Link to the [CelebAMask-HQ dataset](https://github.com/switchablenorms/CelebAMask-HQ/blob/master/README.md) used for this investigation

Link to the original MultiRes-U-Net implementation is [here](https://github.com/nibtehaz/MultiResUNet).

![Demo Picture](/DemoOutput.png)
*Output for a random image using the FD10 model in the project.*
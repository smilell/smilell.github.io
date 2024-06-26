---
layout: page
title: Algorithm Description Guidelines
menubar: home_menu
show_sidebar: false
hero_image: /images/Feta_2024_2.png
---

{% include notification.html
message="The updated guideline for FeTA 2024 will come out soon."
icon="false"
status="is-success" %}


Algorithm Description Guidelines
In addition to submitting a docker container, participants must submit a short description of their algorithm highlighting the main features by August 9, 2022. 

Please fill in the following form: [FeTA Challenge Algorithm Description Submission](https://www.synapse.org/Portal/filehandle?ownerId=syn25649159&ownerType=ENTITY&fileName=Algorithm_submission_instructions.docx&preview=false&wikiId=610007)

In addition to the above form, please provide a description of your model highlighting the main features. This description must include the following details (unless the parameter is not applicable for your model):

-        Model architecture

-        Number of layers

-        Convolution kernel size

-        Initialization

-        Optimizer

-        Cross-validation used?

-        Number of epochs

-        Number of trainable parameters

-        Learning Rate and schedule

-        Loss Function

-        Dimensionality of input/output (ie: 2D,3D, 2D+, etc.)

-        Batch Size

-        Preprocessing steps used (ie data normalization, creation of patches, etc.)

-        Data Augmentation steps (ie – rotation, flipping, scaling, blur, noise, etc.)

-        External dataset used? (allowed, but it needs to be publicly available

-        Framework (ie – MONAI, nnUNet, etc.)

-        Number of models trained for final submission

-        Post-Processing Steps (ie – ensemble network, voting, label fusion)

-        Clearly state which aspects are original work (if any) or already existing work

-        Include relevant citations, as well as if existing code/software libraries/packages were used

-        Which FeTA cases were included in the training and testing (ie – all cases, only pathological, only 1 institution, etc.)

-        Training/validation/testing data splits

-        Hyperparameter tuning performed

-        Training time

 

Note: If your method was not deep learning-based, please provide the equivalent appropriate information as listed above. 
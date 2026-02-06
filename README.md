This project contains 3 main parts implemented using Google Colab for our main analysis (within the ProjectCode folder):

- Final_Project.ipynb: All components needed to load the dataset, run our model, fine-tune the model on the fashion dataset, and achieve the results as described in the final report.
- Ablation.ipynb: All components needed to load the dataset, run our model, fine-tune the model on the fashion dataset, but instead – run the ablation analysis for our final report.
- BoundingBox_Experiment1.ipynb: All components needed to load the dataset, run our model and fine-tune based on hierarchical bounding box loss calculation.


## Requirements: All dependencies are automatically installed in Colab via the notebooks.
- If running locally: pip install torch torchvision matplotlib numpy Pillow diffusers
- We ran everything using a Google Colab T4 environment, please make sure to use GPU on this environment because epochs will take a long time to train. On average, epochs take approximately 20-40 minutes to train.

## Open the notebooks in Google Colab/any IDE:
- Run the cells sequentially, making sure to not skip on any pip installs, imports, or data loading procedures.
- Visualize the baseline InstructPix2Pix model
- Play around with different URLs and prompts if you’d like!
- Load the FashionPedia dataset
- Create the functions for metrics, CLIP Score, Directional Similarity

## Model Preparation
- You can change any hyperparameters at this point, but they will affect runtime length
- Visualize initial output

## Generating Triplets for Fine-Tuning

## Training
- This part will take very long, and needs GPUs. Likely to estimate it will take 1-2 hours at a minimum!

## Evaluation
- Evaluate the output on seen data (DeepFashion), and unseen data with backgrounds (FashionPedia)


## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

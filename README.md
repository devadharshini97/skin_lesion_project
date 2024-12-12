# skin_lesion_project

The notebook is divided into 3 parts for 3 experiments which i have written in the markdown.
To run the app.py script (which gets created automatically the user must have API key for using the models from hugging face)
- part 1 -> running only the clipseg model with the streamlit app (it automatically creates the app.py file which is used for streaming the webpage)
- part 2 -> run the cells for the clipseg finetuning and then run the part 1 cell to create the app.py file
- part 2 -> run the cells for the medseg and then run the part 1 cell to create the app.py file

I have specified the cells with the model names in the jupyter notebook.

Pretty much most part was written by me its pretty basic since i am using pretrained models from the hugging face hub. i also referenced the streamlit resource for the webpage creation but had to do some changes to adapt to the current version of the transformer.

Also make sure to pip install the correct transformer version that is used in the notebook, else the code will not work.

running commands: run the above cells and make sure app.py file is created. Then, it will create a local host url which you can copy and open in a new tab. And then give the lesion image as input. you would get the segmented image and the gpt4 can also answer any question you ask it.

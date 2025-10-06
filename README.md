# Melanoma-Image-Classifier
Image classifier to identify skin melanomas from a variety of mole types. Project for the Official University of Exeter Movember Hackathon 2024. Uses the Skin Cancer MNIST dataset from https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

Be aware this is very raw code and provides no user interface.

## Installation

Download the file 'MovemberHackathon.ipynb'

## Usage

1. Use the convert image cell to convert a taken image to the correct format. Must be done below the final cell.
    '''python
    convert_image(your_heicpath,your_desired_jpgpath)
    '''
2. Test your image using the supernet50 model from stage 4.
    '''python
    single_image_test(your_jpgpath)
    '''

## License

[MIT](https://choosealicense.com/licenses/mit/)



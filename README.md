# <ins>AutoGenerate-NFT-Arts</ins>
This library is a powerful resource for creating nft collectibles by cloning one art into multiple variants, enabling the development of NFT avatars and collectible projects.

### Features
 - #### Generate over a million distinct images with less than 60 traits
The library allows you to generate images every distinct possible combination of your traits. For context, if you had trait art for a project like Bored Apes, the library could generate upwards of 1.2 billion distinct apes.
 - #### Add rarity weights
The library also allows you to configure the image generation process in such a way that you have complete control over how rare each and every trait is.
 - #### Generate compliant JSON metadata for your NFTs
There is now an added functionality to generate JSON metadata for your NFTs that are in compliance with OpenSea metadata requirements (and by extension, the general NFT metadata standard).
 - #### Fuzzy friendly
You can use this library even if you do not know how to program (in Python or otherwise). Do check out the Tutorial for more details on how to use (non-technical) and extend (technical) the library.
### Installation
*Clone this repository

run 
```shell
git clone https://github.com/rounakbanik/generative-art-nft.git
```

* Install required packages
```shell
pip install Pillow pandas progressbar2
```
Next 
-Upload your input assets in the assets folder,
-fill up the config.py file, 
-then run 

```shell
python nft.py
```

In order to generate JSON metadata, define BASE_NAME, BASE_IMAGE_URL, and BASE_JSON in metadata.py and then run python metadata.py.

#Enjoy

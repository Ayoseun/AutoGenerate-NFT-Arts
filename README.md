# <ins>AutoGenerate-NFT-Arts</ins>
This library is a powerful resource for creating nft collectibles by cloning one art into multiple variants, enabling the development of NFT avatars and collectible projects.

### Features
 - #### Generate over a million distinct images with less than 60 traits
The library enables you to create images from every unique combination of your traits. For context, suppose you possess the "art" trait for a project like Crypto Kitties; in such a case, the library has the capability to generate over 1.2 million distinct kitties.
 - #### Add rarity weights
The library also permits you to customize the image generation process, granting you full control over the rarity of each individual trait.
 - #### Generate compliant JSON metadata for your NFTs
JSON metadata feature enables the generation of JSON metadata for your NFTs that adhere to OpenSea's metadata requirements and, consequently, the overarching NFT metadata standard.
 - #### No-Level friendly
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

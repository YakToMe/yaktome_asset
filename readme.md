A visual dictionary mapping visuals to yaktome concept id. Concept id's are english based, like Dog_noun1_1.jpg would be a dog, first meaning of noun, first variant of the picture.

Assets here are mostly language insensitive and named by their english based concept id. Each concept id may have more than one photo, so we can collect ones that are culturally appropriate.

A good process would be to set this repo as a submodule to the language specific repo.

Files in this repository:
1. concept.jpg
2. concept.jpg.json - credits/license for the photo
3. concept.jpg.process.json - instructions for cropping, compressing the base photo to 4:3, 16:9

deploy will then scale this to 1024x768 (typically)

Typical process.json:
{
    "crop_4_3": [ 0, 0, 1024, 768],
    "crop_16_9": [ 0, 0, 1920, 1024],
}

This repo can also contain various lottie files that can be tapped for use in deployments in success or failure sequences.


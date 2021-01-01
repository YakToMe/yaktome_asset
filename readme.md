A visual dictionary mapping visuals to yaktome concept id. Concept id's are english based, like Dog_noun1_1.jpg would be a dog, first meaning of noun, first variant of the picture.

Assets here are mostly language insensitive and named by their english based concept id. Each concept id may have more than one photo, so we can collect ones that are culturally appropriate.

A good process would be to set this repo as a submodule to the language specific repo.

Files in this repository:
1. concept.jpg
2. concept.json - credits/license for the photo
3. process.json - instructions for cropping, compressing the base photo to 4:3.

# this doesn't have to be 1024 by 768, just 4:3.
# deploy will then scale this to 1024x768 (typically)
{
    rect: [ 0, 0, 1024, 768],
}

This repo can also contain various lottie files that can be tapped for use in deployments in success or failure sequences.


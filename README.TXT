Hi, this is just a simple library to download image from https://thispersondoesnotexist.com
The main goal of this library is so user can have easy access to a pretty good human faces and use it for AI training or just a image place holder

to install you just need to "pip install generate-face"

if you want to download 5 picture you can use the script below, just change the number to whatever you like

import generate_face
FaceGenerator = generate_face.FaceGenerator
test = FaceGenerator(5)
test.gen_face()

Notice there is a slight delay to download each picture because this is an unofficial library so i dont want to unintentionally DDOS the server. 

## What is this?

HOT is a short-range / low-rez / low-altitude trained YOLOv8-nano-segmentation model that only detects people IN THERMAL IMAGERY and runs at 640px x 512 px. It's a super basic training run for now.

It's free to use so knock yourself out! Just make sure to follow the Ultralytics terms of service around commercial use (https://github.com/ultralytics/ultralytics) since this uses their code for training.

# Does it work?

It's not bad... it's a nano model so it's super fast for your edge devices. See the video below (although most of the people are occluded here... I should get a better demo video!)
The dataset is mostly eye-level data with some overhead / drone data in there too, for this nano model. This is not meant to be a 100%-drone AI model. I'm training bigger ones but probably won't make them public :)

![output](https://github.com/stephansturges/HOT/assets/20320678/92d0ad59-a60e-45e2-8ef5-5d01758fe4d4)


I'm also working on some larger models that work better... but probably won't be open-sourcing them for the time being. If you want one, contact me ;)


![output](https://github.com/stephansturges/HOT/assets/20320678/e76c50d6-9de8-4dda-b8a1-d3663c059b6c)


## License (MIT)


Copyright 2023 Stephan Sturges

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


<h1>Segmentation for Ms roads</h1>
<h2>Matireals an documentations</h2>
<a href="https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/">about Unet</a><br>
<a href="">Model Unet</a><br>
<h2>From code/about code</h2>
<h3>Unet model</h3>
<img src="./UNET.png">
<h2>Results of programm</h2>
<h3>Prediction for model</h3>
<img src="predict_img.png">
<p>And the final result of segmentation is</p><br>
<img src="results.png">
<h1>Road segmentation project</h1>
<h2>Crop in my code</h2>
<p>In my program I use <a href="https://pytorch.org/vision/stable/generated/torchvision.transforms.RandomCrop.html">random crop</a> in augamentation. That's not thr same with simple crop. That version able to help our model get more information from any parrt of image <a href = "https://blog.roboflow.com/why-and-how-to-implement-random-crop-data-augmentation/">Example</a></p>
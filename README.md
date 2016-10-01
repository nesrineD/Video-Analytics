
* Run a server with the following command:
	
#### Python 2.x

```
$ python -m SimpleHTTPServer 8000 
```

#### Python 3.x

```
$ python -m http.server 8000 
```

Once the server is up, open a web browser and navigate to [http://localhost:8000/](http://localhost:8000/). The demo should start loading.


* Parameters to change:
in:
<video id="video" width="640" height="360" preload controls>
      <source src="video.mp4" />
</video>
video.mp4 is the video to analyse 
Find a screenshot of a result example.
On the right hand side, you find a video capture, on the left hand side you find the image to analyse

Depending on the faces size
var faceMode = affdex.FaceDetectorMode.SMALL_FACES; or var faceMode = affdex.FaceDetectorMode.SMALL_FACES;

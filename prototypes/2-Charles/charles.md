# Charles

Charles is our image-based captcha prototype.
You can add your own set of images by following these rules:
- create a numbered folder (n+1),
- add 9 images,
- images must be 300x300px, .jpg,
- images name must be 1.jpg, …, 9.jpg, 
- add what we're looking for in the object.json file formated as below.

```
{
  "object": "weapons",
}
``` 

Charles can be tested there: https://felicien.io/charles/.
If you want to run it on your machine you need to run a local web server, something like ```python3 -m http.server``` in the folder and visit http://localhost:8000/index.html.
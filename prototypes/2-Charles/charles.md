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
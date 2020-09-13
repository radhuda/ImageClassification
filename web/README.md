# ImageClassification/web

## Dockerfile
Specifies get from docker images python3 and the requirments to be installed via pip

## app 
Provide Api resources such as :

```
/register 
/refill 
/classify
```

## classify_image

This was a template taken from tensorflow inception v3 tutorial. Had to make a few edits due to tensorflow v1 being deprecated. Had to call a lot of the functions via  ```tf.compat.v1```


## requirements
The web application required 
```
Flask
flask_restful
pymongo
bcrypt
numpy==1.18
tensorflow
requests
```

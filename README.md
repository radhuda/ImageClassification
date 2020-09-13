# ImageClassification
Dockerized REST API Image Classification with Inception v3

This app works on macOS, Windows, and Linux.<br>
If something doesn’t work, please [file an issue](https://github.com/radhuda/ImageClassification/issues/new).

## Quick Overview

```sh
git clone https://github.com/radhuda/ImageClassification.git
cd ImageClassification
sudo docker-compose build
sudo docker-compose up
```


Then open [http://localhost:5000/](http://localhost:5000/) to see the app.<br>


### Requirements
```
Python 3
Docker
Docker-Compose
```

### File Structure

```
ImageClassification
├── README.md
├── Image.code-workspace
├── docker-compose.yml
├── .gitignore
├── db
│   ├── Dockerfile
└── web
    ├── Dockerfile
    ├── app.py
    ├── classify_image.py
    └── requirements.txt
```

No configuration or complicated folder structures, just the files you need to build your app.<br>
Once the installation is done, you can open your project folder:

```sh
cd ImageClassification
```

Inside the newly created project, you can run some built-in commands:

### `sudo docker-compose build`
### `sudo docker-compose up`

Runs the app in development mode.<br>
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.

The page will automatically reload if you make changes to the code.<br>
You will see the build errors and lint warnings in the console.


## Acknowledgements

We are grateful to the authors of existing related projects for their ideas and collaboration:

- [@El Farouk Yasser](https://www.udemy.com/user/elfaroukyasser/)
- [@Tensorflow](https://github.com/tensorflow)

## License
TensorFlow, Docker, Flask is open source software

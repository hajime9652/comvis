# visualize social network data
## ENRON Email dataset
pull pre-built image
`docker pull gcr.io/kaggle-images/python:latest`


```
git clone https://github.com/hajime9652/comvis.git
cd comvis
docker-compose run data /bin/bash
mv ./kaggle.json /root/.kaggle/
pip install kaggle update
kaggle datasets download -d wcukierski/enron-email-dataset
unzip enron-email-dataset.zip
```

FROM hydrosphere/odsc-workshop-base:latest

ADD ./train-estimator.py /src/
ADD ./train-resnet.py /src/
ADD ./resnet.py /src/

WORKDIR /src/
CMD [ "python", "train-resnet.py" ]

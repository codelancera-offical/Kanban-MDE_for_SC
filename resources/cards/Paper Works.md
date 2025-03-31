# Paper Works

## BackGround

- Prior works utilized Transformer to model spatio-temporal correlations for videos.
- A naive way to convert spike streams to videos lose temporal continuity

## Goals

- attempt to explore transofrmer to learn the spatio temporal featurs from spike data stream
- Two key points
  1. How to mine the spatio-temporal features from binary, irregular, and continuous spike streams?
  2. How to make full use of Transformer on the unstructured spike data?

## Works

- proposed a new scheme: Spike Transformer
  - learn both s-t spike features
  - then estimate depth from continuous spike streams

- proposed 2 spike-base depth dataset
  - DENSE-spike: synthetic dataset
    - spike streams
    - ground truth depth maps
  - Outdorr-spike: real dataset generate from spiking camera
    - traffic roads / city streets

- present an input spike embedding techique to fit spike data to Transformer
  - equipped with a spatio-temporal patch partition module
  - to maintain features from both spatial and temporal domains

## Main Achievement

1. first attempt to do MDE using ony spike streams
2. first develop 2 spike-base depth dataset
3. propose Spike Transformer (Spike-T)
4. Present a spatio-temporal patch partition module to maintain s-t features

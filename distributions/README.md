# Deploy on Docker

`docker build -t image .`

`docker run -it -v ~/Quantum.fake.detectron/distributions:/sebasmos/model -v ~/Quantum.fake.detectron/data:/sebasmos/data: sebasmos bash`

`python test.py data/ model/`

# tensorFlow
a project to learn TensorFlow.

# install

for windows, Use CPU-Z software to see if the CPU Instruction Set.

if CPU support avx2 then `pip install .\CPU\avx2\tensorflow-1.12.0-cp36-cp36m-win_amd64.whl`,

else if  CPU support sse2 then `pip install .\CPU\sse2\tensorflow-1.12.0-cp36-cp36m-win_amd64.whl`.

the protobuf>3.6.0 get an error using tensorflow==1.12.0, you should use protobuf==3.6.0.


# run
```
python3 example1.py

python2 example2.py

python3 .\fully_connected_feed.py --log_dir logs --input_data_dir MNIST_data
```

# Keras learning

## some error
* pycharm deployment in remote server using tensorflow-gpu python interpreter
    * ImportError: libcublas.so.9.0: cannot open shared object file: No such file or directory
                
              add `LD_LIBRARY_PATH=/usr/local/cuda/lib64:$LD_LIBRARY_PATH` to environment variable

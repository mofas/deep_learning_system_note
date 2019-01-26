### Install python3 kernel

```
python3 -m pip install ipykernel
```

### Install libraries

```
python3 -m pip install tensorflow
python3 -m pip install numpy
python3 -m pip install matplotlib
python3 -m pip install scikit-learn
```

### Solve SSL problem when download MNIST (in python3 environment)

When you have a problem donwload MNIST data.

```
<urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:777)>
```

```
/Applications/Python\ 3.6/Install\ Certificates.command
```

Ref:
https://github.com/tensorflow/tensorflow/issues/10779#issuecomment-318839946

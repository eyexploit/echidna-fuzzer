## Install Echidna using docker 

```shell
docker run -it – rm  -v $PWD:/code/  trailofbits/eth-security-toolbox
```
It starts the docker image and enters the docker terminal
## Run the Echidna test
```shell
cd /code
echidna-test <file name> --test-limit 10000 --contract <contract name>
```

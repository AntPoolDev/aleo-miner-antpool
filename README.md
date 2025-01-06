# *aleo-miner-antpool*
This is a mining tool for ALEO, exclusively for use with ANTPOOL. For more details, please visit https://www.antpool.com/home.


## Requirements

- Download software with specific suffixes according to the version of your operating system. Currently `Ubuntu18.04`, `Ubuntu20.04` and `Ubuntu22.04` is supported
- CUDA version >= 12.0
- A good network environment


## Usage:


```shell
./aleominer_[os_prefix] [OPTIONS] --account <ACCOUNT> --pool <POOL>

Options:
      --account <ACCOUNT>
      --pool <POOL>
  -g, --gpu-index <GPU_INDEX>  [default: 0]
  -h, --help                   Print help


--pool: `aleo.antpool.com:9038`. If you cannot connect to this domain due to DNS pollution, please use the IP address directly: `172.65.162.169:9038`

--account：The account of Antpool and your workername, which are separated by a dot. Example: aleo123.8x4090

-g: The GPU indice which you want to mining. Optional. Default: 0. Examples: -g 0,1,2,3,4,5,6,7
```

### Example

```shell
./aleominer_ubuntu22_04 --account aleo123.8x4090 --pool 172.65.162.169:9038 -g 0,1,2,3,4,5,6,7
```

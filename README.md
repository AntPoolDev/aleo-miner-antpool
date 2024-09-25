# aleo-miner-antpool
This is a mining tool for ALEO, exclusively for use with ANTPOOL. For more details, please visit https://www.antpool.com/home.

Usage:

./antpool_prover --pool aleo.antpool.com:9038 --account account_name  --custom_name worker_name

--pool：		The pool’s address. Example:  aleo.antpool.com:9038，

--account：		The account of Antpool. Example：test

--custom_name:	The workername of your account. Example：001

--gpu_index: 		The GPU indice which you want to mining. Optional. Default: All available GPUs. Examples: –gpu_index 0


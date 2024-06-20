# alignedlayer-testnet-proof  

![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/42258669-d821-44c4-a646-e6572c39bbaf)


## Getting Srtarted 

```
sudo apt update -y
sudo apt upgrade -y
```

### Install curl 
```
sudo apt-get install curl -y
```

### Download ALignedProof 
![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/d3ec8a6a-adcf-48f5-a72f-b794c3290440)

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```

```
source /root/.bashrc
```


### Download an example SP1 proof file with it's ELF file 
![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/79105b35-f907-435b-966d-0ec00cac6f18)


```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```


### Sending proof 

![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/0a59b7e8-2f75-4882-b333-ebb43547089a)

```
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```

use this code to get the log you will screenshot for your X post
```
aligned verify-proof-onchain \
--aligned-verification-data ~/aligned_verification_data/*.json \
--rpc https://ethereum-holesky-rpc.publicnode.com \
--chain holesky
```


Use the explorer link in CMD to check if verified and you'll also see below image. 
![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/fd570acb-5b6f-481e-b9b0-d0bd3143fc51)

![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/1ff9c16b-bb01-4e9d-8b68-6ae102af79b4)



-------------
----------------------
### Tweet exactly as screenshot and Submit Proof in Dscord 

![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/266a2616-e364-4221-8ac5-1f100b842048)



--------------------------
### Submit in Discord 
![image](https://github.com/Ravindrareddy161/alignedlayer-testnet-proof/assets/152148394/8e528352-9716-4e43-8427-ada4dde3dff7)




# JOIN DISCORD FROM PROFILE 
https://linktr.ee/AlignedLayer





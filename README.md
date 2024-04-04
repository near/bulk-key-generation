# bulk-key-generation
bash script to automate bulk key generation, adding them to an account, and putting the credentials into a JSON

## Run
1. [Install near-cli-rs](https://github.com/near/near-cli-rs/releases/)
2. Make sure you're using the appropriate network: `echo $NEAR_ENV`. To change it, `export NEAR_ENV=testnet`
3. run `chmod 755 bulk_keygen.sh`
4. run `./bulk_keygen.sh`

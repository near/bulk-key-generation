# bulk-key-generation
bash script to automate bulk key generation, adding them to an account, and putting the credentials into a JSON

## Run
1. [Install near-cli-rs](https://github.com/near/near-cli-rs/releases/)
2. login to the account you will be using by running: `near login`
3. Make sure you're using the appropriate network: `echo $NEAR_ENV`. To change it, `export NEAR_ENV=testnet`
4. run `chmod 755 bulk_keygen.sh`
5. run `./bulk_keygen.sh`

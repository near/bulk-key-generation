# bulk-key-generation
Bash script to automate bulk key generation, adding them to an account, and putting the credentials into a JSON.

This is useful for high throughput applications on NEAR that may be encountering nonce errors due to concurrency. By generating lots of keys and adding them to your account, you can round robin rotate through them to fix nonce errors due to concurrency. 

## Run
1. [Install near-cli-rs](https://github.com/near/near-cli-rs/releases/)
2. Make sure you're using the appropriate network: `echo $NEAR_ENV`. To change it, `export NEAR_ENV=testnet`
3. run `chmod 755 bulk_keygen.sh`
4. run `./bulk_keygen.sh`

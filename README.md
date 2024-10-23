# hello-world-action
git action test

# self-runner
```shell
 $ mkdir actions-runner && cd actions-runner
 $ curl -o actions-runner-osx-x64-2.320.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.320.0/actions-runner-osx-x64-2.320.0.tar.gz
 $ echo "11e610adc1c3721a806d2a439d03d143cceeda7a63e794bfe75b45da55e308df  actions-runner-osx-x64-2.320.0.tar.gz" | shasum -a 256 -c
 $ tar xzf ./actions-runner-osx-x64-2.320.0.tar.gz
 $ ./config.sh --url https://github.com/Mavin-chaebin/hello-world-action --token <git-token>
 $ ./run.sh
 ```
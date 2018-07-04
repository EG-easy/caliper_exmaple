# caliper_example
I just modify a little of caliper repository for making benchmark in many situations.

you can make benchmark in the below docker container.

*2org1peer
*2org2peer
*2org3peer
*3org1peer
*3org2peer
*3org3peer

You can start 2org1peer benchmark with below command.

```ruby:caliper/
node benchmark/simple/main.js -c config-fabric-2.1.json
```

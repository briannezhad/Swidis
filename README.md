# Swidis
## Redis Swift Framework
iOS Framework Allowing you to connect to Redis server with Swift programming language. Thanks to [GCDAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket), We are working on Redis Framework in Swift 2.

### Install
Just add the framework to your project for both Simulator and iOS Device (Or which ever you desire).

#### Create Constant of Class Swidis: 
`let redis = Swidis()`

#### Configure Redis Server: 
`redis.server("XXX.XX.XXX.XXX", onPort: 6379)`

#### Send Commands [We are working on other Commands :)].
`redis.Command("SET a "Apple"")`

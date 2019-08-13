# NexmarkAuctionStreamProcessor

The Nexmark benchmark provides a data generator that models the state of an auction in XML format, and various queries
over the generated data. More details on this data generator can be found [here](https://beam.apache.org/documentation/sdks/java/testing/nexmark/#what-it-is)

NexmarkAuctionStreamProcessor is designed to generate the auction data such that the data can be sent to a kafka topic.There are 3 major streams of data as Person, OpenAuction and Bid.

### Build the Benchmark
```
mvn clean install -Dcheckstyle.skip=true -Dfindbugs.skip=true
```

### Run the Benchmark
```
sh run-loader.sh
```
# NexmarkAuctionStreamProcessor-dynamic-datarate-patterns

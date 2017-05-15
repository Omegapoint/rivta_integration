# Rivta Integration

## Build
`cd rivta_integration`
`mvn install`

## Run

### Producer 
`cd rivta-bp21-refapp-producer`
`mvn -e exec:java -Dexec.mainClass="se.skl.rivta.bp21.refapp.producer.Server"`

### Consumer
`cd rivta-bp21-refapp-consumer`
`mvn -e exec:java -Dexec.mainClass="se.skl.rivta.bp21.refapp.consumer.crm.scheduling.Initiator"`

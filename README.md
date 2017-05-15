# Rivta Integration

## Build
 1. `cd rivta_integration`  
 2. `mvn install`

## Run

### Producer 
 1. `cd rivta-bp21-refapp-producer`  
 2. `mvn -e exec:java -Dexec.mainClass="se.skl.rivta.bp21.refapp.producer.Server"`  

### Consumer
 1. `cd rivta-bp21-refapp-consumer`  
 2. `mvn -e exec:java -Dexec.mainClass="se.skl.rivta.bp21.refapp.consumer.crm.scheduling.Initiator"`  

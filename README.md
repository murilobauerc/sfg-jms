# sfg-jms
Playing around JMS API and its implementations.

## To run ActiveMQ with AMQP, JMS and the web console open (if your are running 2.3.0 or later), run the following command:

   docker run -it --rm \
     -p 8161:8161 \
     -p 61616:61616 \
     vromero/activemq-artemis
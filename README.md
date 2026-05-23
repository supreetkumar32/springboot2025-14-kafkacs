kafka

in the postman(kafka server should be running in the background) if we test http://localhost:9050/users/hello , it will return message queued

now consumer is also created
if we hit the url http://localhost:9050/users/hello through postman ,we get the message in the terminal of spring boot

now , 1000 messages are sent
hit the url
messages are printed in the terminal of spring boot(messages are distributed among 3 listeners in the UserKafkaConsumer class)
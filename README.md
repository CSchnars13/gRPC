Epic gRPC Multiplayer Online MMORPG Strategy FPS Game of the Year Best in Show

Build

1. Comment out the modules in the top level pom to build the parent artifact locally with mvn clean install
2. Uncomment and run mvn clean install again to build the modules
3. With two terminals, run:
java -cp target/grpc-server-1.0.0-SNAPSHOT-jar-with-dependencies.jar com.clubbis.grpc.AppServer
java -cp target/grpc-client-1.0.0-SNAPSHOT-jar-with-dependencies.jar com.clubbis.grpc.Client


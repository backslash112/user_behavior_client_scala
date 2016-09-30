# User Behavior Client(Producer)
A practice with https://www.ibm.com/developerworks/cn/opensource/os-cn-spark-practice2/

### Build the SBT project:
Step 1: Start a sbt docker container:

    docker run -it --rm -v $(pwd):/workspace -w /workspace hseeberger/scala-sbt

Step 2: Run the sbt project:

    sbt
    > run 192.168.1.1:9002 user-behavior-topic

### The Server
https://github.com/backslash112/user_behavior_server_scala

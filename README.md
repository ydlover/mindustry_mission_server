# mindustry_mission_server
javac -cp ./server-release_75.jar -sourcepath ./ io/anuke/mindustry/server/ServerControl.java 
javac -cp ./server-release_75.jar -sourcepath ./ io/anuke/mindustry/core/World.java
jar uvf ./server-release_75_mission.jar io/anuke/mindustry/core/World.class
jar uvf ./server-release_75_mission.jar io/anuke/mindustry/core/World$Raycaster.class
jar uvf ./server-release_75_mission.jar io/anuke/mindustry/server/ServerControl$1.class
jar uvf ./server-release_75_mission.jar io/anuke/mindustry/server/ServerControl$2.class
jar uvf ./server-release_75_mission.jar io/anuke/mindustry/server/ServerControl.class


# Checkpoint 7 - Mission Reflection

A Docker container boots in seconds because it shares the host operating system. A Virtual Machine takes much longer to boot since it require installing a full guest OS. You must allocate heavy memory to a VM. Containers saves time and they use less system resources. This speed change how we deploy applications.

Port mapping connect the host machine to the container. The command `-p 8080:80` links host port 8080 to container port 80. The container runs in an isolated network, which block external access by default. Without port mapping, outside traffic cannot reach the web server and users would see a broken connection. Mapping open a specific door for web traffic.

The `docker rm` command completely deletes the stopped container. This action wipe all temporary data inside it. The container throws away any changes made during its run, so you lose any new files you created inside. You must save important data to a permanent host volume. A volume keep data safe even after you remove the container.

Containers helps software developers and IT operations teams work better together. Developers write code inside a standard container. IT teams run that exact same container on the production server, which stop the common problem where code fails on different computers. Both teams use the same environment. They deploy software faster and makes fewer errors during deployment.

My GitHub portfolio show a much wider range of skills now. I previously uploaded my markdown notes documenting Linux cloud server commands. Now, I am adding cloud-native container deployments. My repository prove I can build mobile application layouts while also showing I can manage modern backend cloud services. My portfolio tell a complete story of my technical growth.
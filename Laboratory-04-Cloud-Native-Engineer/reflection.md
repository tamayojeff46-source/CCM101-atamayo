# Laboratory Reflection

The boot time and setup process of a Docker container are significantly faster than installing an operating system on a Virtual Machine. While a virtual machine requires booting a full guest OS kernel, emulating hardware, and going through a lengthy installation wizard, a Docker container shares the host system's kernel and only loads the application binaries and libraries, allowing it to start up in mere seconds.

Port mapping, such as `-p 8080:80`, is necessary because containers run inside an isolated network sandbox. Without mapping, network traffic from the host machine cannot reach the internal ports where the application inside the container is listening. This parameter bridges port 8080 on the host to port 80 inside the container, enabling external access to the web server.

When you use the `docker rm` command, any data stored inside the container's writable layer (non-persistent storage) is permanently deleted along with the container. To retain data past the life of a container, developers must use Docker volumes or bind mounts to store data safely on the host machine.

Containerization transforms how software developers and IT operations teams collaborate by bridging the "it works on my machine" gap. Developers can package code, dependencies, and configurations into a single standardized container image, ensuring that it behaves identically across development, testing, and production environments handled by operations.

Finally, my GitHub portfolio is steadily evolving from a simple code repository into a comprehensive, professional showcase of cloud-native engineering tasks, automation scripts, and technical documentation, reflecting my ongoing growth as an IT student.

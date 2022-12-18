## Quiz Questions


#### Q-1 Why do Linux containers use union file systems?

- [ ] To control an application's maximum consumption of CPU time and memory
- [ ] To give a container its own virtual memory address space
- [x] To efficiently encapsulate applications and their dependencies into a set of clean, minimal layers
- [ ] To control an application's ability to see parts of the directory tree and IP addresses


#### Q-2 What is significant about the topmost layer in a container? Choose all that are true (2 correct answers).

- [x] The topmost layer's contents are ephemeral. When the container is deleted the contents will be lost.
- [ ] Reading from or writing to the topmost layer requires special software libraries.
- [x] An application running in a container can only modify the topmost layer.
- [ ] Reading from or writing to the topmost layer requires special privileges.

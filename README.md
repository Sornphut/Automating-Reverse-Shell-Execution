# Automating-Reverse-Shell-Execution
Instead of executing commands one by one, we can use the exploit to send a reverse shell payload, which will give us persistent access.

First, we have to start a reverse shell listener in our VM or AttackBox that will catch the connection using the command:

nc -lvnp 4444

python 3.8.10

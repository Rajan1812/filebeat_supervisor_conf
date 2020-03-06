filebeat_supervisor_conf
This is the configuration for supervisor to start FileBeat.

# What is supervisor?

Supervisor is a client/server system that allows its users to control a number of processes on UNIX-like operating systems. Processes can be grouped into “process groups” and a set of logically related processes can be stopped and started as a unit. It starts its subprocesses via fork/exec and subprocesses don’t daemonize. The operating system signals Supervisor immediately when a process terminates.

You'll have to add the config in the "/etc/supervisor.conf" or create a new directory /etc/supervisord/filebeat.conf and then add the config

Incase you are using any custom path for supervisor config. You can put the detaisl there.

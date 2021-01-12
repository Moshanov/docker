# Docker containers
	* Payara app/server
	* mariadb
	* lib-auth services

# useful commands
	docker build -t payara .
	docker run -p 4848:4848 -p 8080:8080 payara
	...
all: data db wp up

up:
	docker-compose -f ./srcs/docker-compose.yml up -d
data:
	mkdir /home/hyalcink/data
db:
	mkdir /home/hyalcink/data/db
wp:
	mkdir /home/hyalcink/data/wp

down:
	docker-compose -f ./srcs/docker-compose.yml down

.PHONY: up data db wp down

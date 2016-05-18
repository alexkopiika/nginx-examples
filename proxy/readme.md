### run nginx in docker container
	docker run --name nginx -p 8080:80 -v /home/alex/data/nginx/nginx.conf:/etc/nginx/nginx.conf:ro -v /home/alex/data/nginx:/var/log/nginx -d nginx

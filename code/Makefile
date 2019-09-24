build-1:
	docker build -t characters services/characters/.
build-2:
	docker build -t locations services/locations/.	
deploy-1:
	kubectl apply -f recipes/characters.yaml
deploy-2:
	kubectl apply -f recipes/locations.yaml	
##### How to run the app locally
(i)	First clone the repository using Git clone.
(ii)	Change the API endpoint to localhost instead of 0.0.0.0
(iii)	Run npm i && npm start on the frontend and backend directories after giving openweather app API key to the APP-ID.
Once the app is up, you can expect to see a big icon based on the current climate at the mentioned location which is Helsinki in this case.

##### Docker
Project can be run using the command docker-compose up in the main project folder.

##### Task done
[Done] Docker file’s in the frontend and the backend directories to run them virtually on any environment having docker installed. It should work by saying e.g. docker build -t weatherapp_backend . && docker run --rm -i -p 9000:9000 --name weatherapp_backend -t weatherapp_backend. If it doesn't, remember to check your api key first.
[Done] Add a docker-compose.yml -file connecting the frontend and the backend, enabling running the app in a connected set of containers.
[Partially done] Set up the weather service in a free cloud hosting service, e.g. AWS or Google Cloud. URL will be shared via email

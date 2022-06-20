# PLMore Content Delivery Network.

This part will hold the backend application that streams the videos chunk by chunk to the frontend apps to enhance the content load time.

This app is deployed by a pipeline via a container on heroku:
https://plmore-cdn.herokuapp.com

Heroku has cold starts enabled for the free version. So if the videos are slow to load on the websites, that's because the container is experiencing a cold start. After a bit the CDN should be at an acceptable performance.
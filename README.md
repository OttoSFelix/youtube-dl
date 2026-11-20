# Download content from YouTube in mp3 or mp4 format
# Powered by ![docker](https://img.shields.io/badge/docker-257bd6?style=for-the-badge&logo=docker&logoColor=white)

## Usage

Clone the repository and build the services with `docker compose build`

Run the desired service with docker compose run <service> "<youtube_link>"

### Video

Downloads an mp4 video from the given link
`docker compose run video "<youtube_link>"`

### Audio

Downloads an mp3 audio from the given link
`docker compose run audio "<youtube_link>"`

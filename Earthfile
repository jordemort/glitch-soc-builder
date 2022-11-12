VERSION 0.6
ARG CONTAINER_TAG=latest

glitch:
  FROM DOCKERFILE ./mastodon
  VOLUME ["/opt/mastodon/public"]
  SAVE IMAGE --push ghcr.io/jordemort/glitch-soc-builder:${CONTAINER_TAG}

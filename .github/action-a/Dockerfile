FROM debian:9.5-slim

LABEL "com.github.actions.name"="Github Actions"
LABEL "com.github.actions.description"="Just a demo for Github Actions"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="green"

LABEL "repository"="https://github.com/vineetchoudhary/Github-Actions-Demo"
LABEL "homepage"="https://github.com/vineetchoudhary/Github-Actions-Demo"
LABEL "maintainer"="Vineet Choudhary <vineetchoudhary@live.in>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]

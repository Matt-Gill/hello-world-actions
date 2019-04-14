FROM debian:9.5-slim

LABEL "com.github.actions"="Hello World"
LABEL "com.github.description"="Write arguments to the standard output"
LABEL "com.github.icon"="mic"
LABEL "com.github.color"="purple"

LABEL "repository"="http://github.com/octocat/hello-world"
LABEL "homepage"="http://github.com/actions"
LABEL "maintaier"="Octocat <octocat@github.com>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]

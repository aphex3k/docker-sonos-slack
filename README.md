<b style="color: #1383de">docker</b>&nbsp;+&nbsp;<b style="color: white;background-color: black">&nbsp;SONOS&nbsp;</b>&nbsp;+&nbsp;<b style="color: #1383de">Slack</b>

Slack me what song is currently playing on the Sonos. Basically [sonos-slack](https://github.com/aphex3k/sonos-slack.git) running in docker.

## Usage
Example command:

    docker run --rm aphex3k/docker-sonos-slack --env GOOGLE_API_TOKEN=foo --env GOOGLE_CX_TOKEN=bar --env SLACK_API_TOKEN=baz

Please make sure to replace <em>foo</em>, <em>bar</bar> and <em>baz</em>.

[![Build Status](https://travis-ci.org/aphex3k/docker-sonos-slack.svg?branch=master)](https://travis-ci.org/aphex3k/docker-sonos-slack)

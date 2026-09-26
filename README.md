# Pearnify Playwright QA reports

Published test reports for [Pearnify](https://pearnify.com), so a result in
Slack can be opened rather than downloaded.

Reports appear under `playwright/<environment>/`, with `latest/` alongside a
folder named after the release it came from.

## What is here, and what is not

Each report lists every test, whether it passed, and the error if it did not.

Traces are deliberately left out. A Playwright trace records the whole
exchange between the suite and the API, including authorisation headers and
request bodies, and none of that belongs in a public place. They are kept on
the workflow run itself, where only the Pearnify repository can reach them.

This repository holds no source code and nothing is deployed from it.

# Odin website build

Synthetic repository for a DevOps artifact publishing exercise.

## Tester handoff

Open Actions, select the latest Build website run, and download the
`website-build` artifact from the run summary. Extract it and open `index.html`
in your browser. The expected page title is Odin Test Build and the visible
build identifier is `ODIN-DEMO-001`. The preview should have a blue top border.

## Reported issue

Testers cannot find a downloadable website artifact after the workflow completes.
Investigate the run logs and workflow configuration, repair publishing, and
verify the downloaded website files.

## Running the workflow

The workflow runs on pushes. It can also be started from Actions using
Run workflow after the workflow is present on the repository's default branch.

All content in this repository is synthetic and contains no credentials.

This script exports a GitHub user's starred repositories (URL & description) to a CSV file.

Usage: `python3 export_stars.py --user username > stars.csv`

I recommend to use python virtual environment for the operation of this script:
`git clone $repo_url`
`cd export_stars`
`python3 -m venv .venv`
`source .venv/bin/activate`
`python3 -m pip install -r requirements.txt`

Thanks to the authors of [PyGitHub](https://github.com/PyGithub/PyGithub) for the slick client library.

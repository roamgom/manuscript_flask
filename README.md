# Manuscript Flask API server

## usage

**Setup**

```console
$ git clone https://github.com/roamgom/manuscript_flask.git
$ pip install -r requirements.txt
```

**Deploy**

It use fabric to deploy, to deploy

edit value in `deploy.json`

```json
{
  "REPO_URL": "git@github.com:roamgom/manuscript_flask.git",
  "PROJECT_NAME": "manuscript",
  "REMOTE_HOST": [HOST_DOMAIN],
  "REMOTE_HOST_SSH": [IP_ADDRESS],
  "REMOTE_USER": [USERNAME]
}
```

```console
fab deploy
```
# lasc-backend


## Steps to Deploy

- Git clone this repo
- `pip install pipenv`
- `cd lasc-backend`
- `pipenv install`
- `tmux a`
- `pipenv shell`
- `scp client_secret.json root@<ip>:~/lasc-backend`
- `python app.py --noauth_local_webserver`
- Copy URL in console and open in the browser. Approve request for permissions. Copy code and paste back in console.
- Detach Tmux and exit ssh session

# https://creio.gitlab.io/cvc

```sh
git clone https://gitlab.com/creio/cvc.git
cd cvc

pacman -S python-pip

pip install --upgrade virtualenv

virtualenv ve
source ve/bin/activate

pip install -r requirements.txt

mkdocs serve
```

http://127.0.0.1:8000
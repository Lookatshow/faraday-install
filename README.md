# faraday-install
Test Faraday Ub

`
sudo apt install python-dev, libpq-dev
sudo apt install python3-virtualenv

$ virtualenv faraday_venv

$ source faraday_venv/bin/activate

$ git clone https://github.com/infobyte/faraday.git

$ cd faraday

$ git clone https://github.com/infobyte/faraday_angular_frontend.git faraday/frontend

$ pip install .
`


# Фиксим ошибки

`AttributeError: module 'virtualenv.create.via_global_ref.builtin.cpython.mac_os' has no attribute 'CPython2macOsArmFramework'`

Удаляем: pip3 uninstall virtualenv


`ERROR: Command errored out with exit status 1: python setup.py egg_info Check the logs for full command output.`

Обновляем: python -m pip install --upgrade pip и pip install -U setuptools

`Error: pg_config executable not found.`


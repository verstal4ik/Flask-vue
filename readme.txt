install venv
pip install -r req.txt
cd project
export FLASK_APP=start.py
export FLASK_DEBUG=1
flask run
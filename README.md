## Setup & Installation 👀
python -m venv venvapp

venvapp/Scripts/activate
Downloading packages from ```requirements.txt``` inside ``App`` folder
cd../..
cd App
pip install -r requirements.txt
python -m spacy download en_core_web_sm

```

After installation is finished create a Database ```cv```

And change user credentials inside ```App.py```
https://github.com/AI-Resume-Analyzer/blob/17e1cdb207fef62557dc394f4158bda515e541fd/App/App.py#L95

Go to ```venvapp\Lib\site-packages\pyresparser``` folder

And replace the ```resume_parser.py``` with ```resume_parser.py``` 

which was provided by me inside ```pyresparser``` folder
streamlit run App.py
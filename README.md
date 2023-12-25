# openai
Hello world with openai

## Create github repo. 

- Create a repo in github 
- clone it in the devbook
- Open it in codium 

```
kaunjovi@devbook code % git clone git@github.com:kaunjovi/openai.git
Cloning into 'openai'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```

- Choose your coding language of choice. 
- I am choosing Python for this. 
- Do it again for the 3.12 version please. 

```
kaunjovi@devbook openai % python --version 
Python 3.10.2
kaunjovi@devbook openai % pipenv --version 
pipenv, version 2023.11.15
```

- Use pipenv to get run latest python. Dont touch the default of mac. 
- *Manually create a .venv folder*. Else the dependencies will not be local. 


```
kaunjovi@devbook openai % pipenv install --python 3.12
kaunjovi@devbook openai % pipenv shell 
(openai) kaunjovi@devbook openai % python --version 
Python 3.12.1
pipenv install openai

```

- Create your private API keys 
- https://platform.openai.com/api-keys
- export OPENAI_API_KEY=<the key from openai>

# Rough 

- Some useful commands with pipenv 

```
pipenv shell 
pipenv install 
pipenv uninstall 
install --dev autopep8
uninstall django
pipenv --rm
```

- New APIs. https://cookbook.openai.com/
- [OpenAI API reference](https://platform.openai.com/docs/api-reference/authentication)



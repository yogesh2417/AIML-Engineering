# Download Ollama setup application from below link and follow install wizard 

`https://ollama.com/download/windows` --Ollama application setup link

Once installed execute below command in cmd to run ollama

`ollama run llama3.2`

# Use docker image if docker deamon is running locally.

`docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama`  --docker command
`docker exec -it ollama ollama run llama3.2` -- After Ollama container running

# Create virtual environment to isolate project specific dependencies

`python -m venv venv`

# Activate virtual environment

`.\venv\Scripts\activate.bat` -- in cmd
`.\venv\Scripts\activate.sh` -- in ps

# Install all the project dependencies

`pip install -r requirements.txt`
Extract knowledge_base folder

# Use Jupyter Lab to work either download extension and setup python kernel in Visual Code or download package from pip `pip install jupyterlab`. After downloading Jupyter Lab from pip, run `jupyter lab` command.



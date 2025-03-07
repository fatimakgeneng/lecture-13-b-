Default poem_crew ran using lightest DeepSeek Model installed locally using Ollama

## Dowload Ollama from here:
https://ollama.com/download

## Then install DeepSeek model using this:
`ollama run deepseek-r1:1.5b`

Setting up `MODEL` and `BASE_URL` is .env file is very crucial make sure that both are correct.
You can check the exact BASE_URL via command
`ollama ls`

# Miscellaneous
create a crewai project using
`crewai create flow project name`
Note: for this command to work crewai should be installed globally in in your PC using command.
`pip install crewai` i.e. terminal should be run as administrator.
You can check if crewai is installed this way using `crewai --version`


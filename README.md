pkg install git make libjpeg-turbo go-lang

pkg install golang

git clone --depth 1 https://github.com/ollama/ollama.git

cd ollama

go generate 

./...go build .

./ollama serve &

./ollama run deepseek-r1:1.5b

#STOP
/bye

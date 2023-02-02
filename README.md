# simple magenta-docker(cpu)

python with magenta without gpu
for only generate not training

# introduce(docker-compose による立ち上げ)

1.docker-compose build --no-cache  
2.docker-compose up -d  
3.docker-compose exec magenta bash
4.python benzaiten_starter.py

# download mag files(重みファイルなど)

https://github.com/magenta/magenta/tree/main/magenta/models/melody_rnn  
download pre-trained area which you like  
[maggenta-command](./magenta_command.md)

# benzaiten-starter

https://colab.research.google.com/drive/1isnq_E2Mc-Fzeb8DKzYGL39l-B30AwZK  
python benzaiten_starter.py

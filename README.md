# HLC4
Highload Course. Ex 4

1. В папці prb_wrapper знаходиться реалізація probabilistic cache на .ner core
2. В папці siege знаходиться urls.txt та конфіг
3. Результати - https://docs.google.com/spreadsheets/d/1f9Wojs7kvqz0emD5VujmtqBH7izGC4PRicikJXajeRw/edit?usp=sharing
4. Команда - docker run -it --rm -v $(pwd):/app ecliptik/docker-siege -c 50 -f /app/urls.txt -R /app/siege.conf

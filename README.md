Pour avoirs les pré-requis SA12 : 

<https://htmlpreview.github.io/?https://github.com/pushou/presae12/blob/main/html/rappels-et-infos.html>

<https://htmlpreview.github.io/?https://github.com/pushou/presae12/blob/main/html/git-crash-courses.html>

Mémo: générer un fichier html à partir du MarkDown
```bash
docker run --rm --init -v $PWD:/home/marp/app/ -e MARP_USER="$(id -u):$(id -g)"  -e LANG=$LANG marpteam/marp-cli ./markdown/rappels-et-infos.md --pdf
```
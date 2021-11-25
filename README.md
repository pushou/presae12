Pour avoirs les pré-requis SA12 : 
https://htmlpreview.github.io/?https://github.com/pushou/presae12/blob/main/rappels-et-infos.html

pour générer un fichier html à partir du MarkDown
docker run --rm --init -v $PWD:/home/marp/app/ -e MARP_USER="$(id -u):$(id -g)"  -e LANG=$LANG marpteam/marp-cli ./rappels-et-infos.md --pdf

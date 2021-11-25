pré-requis SA12 voir: 
https://htmlpreview.github.io/?https%3A%2F%2Fgithub.com%2Fpushou%2Fpresae12%2Fblob%2Fmain%2Frappels-et-infos.html=#1
pour générer un fichier html à partir du MarkDown
docker run --rm --init -v $PWD:/home/marp/app/ -e MARP_USER="$(id -u):$(id -g)"  -e LANG=$LANG marpteam/marp-cli ./rappels-et-infos.md --pdf

## Labo 1:
# 1 eres CMD

docker run --rm bash echo Salut -> docker = nom cmd
                                    run = action à exec (ici creer et lancer un container)
                                    -- rm = param optionnel qd le container aura fini de s'executer on le supp
                                    bash = le nom de l'img
                                    echo salut cmd à executer ds container

docker images -> affichage de la liste des images présentes dans notre cache

docker run --rm bash:3.2 echo Salut -> execute la version que l'on souhaite

docker run -ti --rm bash -> permet interagir avec le container directement (on est dans le container et non plus sur la michine hôte)

uname -n -> donne le nom de la machine

docker ps  -> liste containers créés
Tutorial : 
https://www.rabbitmq.com/tutorials/tutorial-two-dotnet.html

Notion de dispatch : 
Par défaut, lorsque que plusieurs clients sont en écoute sur la même queue, RMQ dispatche le 1er message à l'un, puis à l'autre..

Notion d'acquittement : 
Par défaut, RMQ envoie le message à un consumer et l'oublie (fire and forget)
Mais si le consumer meurt, le message est perdu.
C'est pour cela qu'on peut parametrer RMQ avec l'option d'acquittement.

Notion de durabilité de la queue : 
Si RMQ stoppe, aun redémarrage la queue existera toujours.

Notion de persistence du message : 
Même chose pour pour un message.


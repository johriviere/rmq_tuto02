Tutorial : 
https://www.rabbitmq.com/tutorials/tutorial-two-dotnet.html

Notion de dispatch : 
Par d�faut, lorsque que plusieurs clients sont en �coute sur la m�me queue, RMQ dispatche le 1er message � l'un, puis � l'autre..

Notion d'acquittement : 
Par d�faut, RMQ envoie le message � un consumer et l'oublie (fire and forget)
Mais si le consumer meurt, le message est perdu.
C'est pour cela qu'on peut parametrer RMQ avec l'option d'acquittement.

Notion de durabilit� de la queue : 
Si RMQ stoppe, aun red�marrage la queue existera toujours.

Notion de persistence du message : 
M�me chose pour pour un message.


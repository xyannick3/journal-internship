#todolist



- do theoretical exercises in Platon 
	- ~~structure of Platon exercice~~
	- ~~the four steps of a PLATON exercice : 
		- ~~construction : builder~~
		- ~~display using ttile wordes such as title statement and form ~~
		- ~~evaluation grader~~
		- ~~solution using solution ~~
	- metadonnée 
	- ~~platon_log~~
	- builder
	- grader
	- ~~le langage ple~~ 

- latex parser : 
	- lire documentation [www.auto-multiple-choix.net]()
	- apprendre à maitriser pylatexenc
	- ~~écrire une fonction qui affiche graphiquement l'arbre ~~
	- on ne veux pas garder les valeurs d'environnement LATEX sauf element
	- on veut garder les contenus textuelles 
	- ~~prévoir que les gens utilisent aussi good bad answer explaination ~~
	- I have to implement questionmult 
	- I have to look up what '\alafin' does
	- I have to implement includegraphics
	- I have a "begincenter" to deal with : proposition, for all environments which aren't the ones I need we just go and access the child and """ignore""" it 
	- I think the next big step is to implement a dictionnary which will contain other dictionaries, a bit like a json file generated from the .tex file
	- problème à régler : lorsque on parcours le node question on parcours la consigne d'une manière plutôt random, je pense que c'est risqué et il faudrait que je le refasse. 
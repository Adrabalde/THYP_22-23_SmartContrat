# THYP_22-23_SmartContrat


# eVote
Système de vote électronique basé sur la blockchain



Conditions :

[Node.js] : (https://nodejs.org/en/)

[Truffle] : https://trufflesuite.com/truffle/

[Ganache (Cli)] : https://github.com/trufflesuite/ganache

[Metamask]: (Extension de navigateur)](https://metamask.io/)

1- 

Téléchargez et installez NodeJS à partir d'ici : https://nodejs.org/en/download/

2- 

Installez truffle et ganache-cli à l'aide du gestionnaire de packages de nœuds (npm)

npm install -g truffle

npm install -g ganache-cli

Installer l'extension de navigateur metamask


Téléchargez et installez le métamasque à partir d'ici : https://metamask.io/download/




Configuration du projet pour le développement

1 - 
Cloner ce dépôt


git clone https://github.com/Adrabalde/eVote.git

cd eVoting

Exécutez la blockchain Ethereum locale


2- 
ganache-cli

Note: Ne fermez pas ganache-cli (le réseau blockchain doit fonctionner tout le temps)

3- 
Configurez le métamasque sur le navigateur avec les détails suivants

Nouvelle URL RPC: http://localhost:8545

ID de chaîne: 1337

4- 
Importer des comptes à l'aide de clés privées de ganache-cli vers l'extension metamask sur le navigateur

5- 
Déployer un contrat intelligent sur le réseau blockchain (local) (c'est-à-dire ganache-cli)

# Sur le répertoire eVoting :

truffle migrate

Note: Pour les redéploiements, Utiliser :  

truffle migrate --reset           

6- 
Lancer le serveur de développement (frontend)

cd client

npm install

npm start


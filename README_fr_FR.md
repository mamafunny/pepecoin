<h1 align="center">
<img src="https://i.imgur.com/DDkfI9i.png" alt="Bonkcoin" width="300"/>
<br/><br/>
Bonkcoin Core [BONC, Ᵽ]  
</h1>

Choisir la langue : [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | FR | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Contrairement à toutes les itérations précédentes, Bonkcoin est une monnaie dite « layer 1 ». Cela signifie qu'il n'y a pas de pools de liquidités à drainer, pas de portefeuilles blacklistés, et pas de contrats intelligents obscurs. Le Bonkcoin est une blockchain simple.

Le logiciel Bonkcoin Core permet à quiconque d'opérer un nœud au sein des réseaux de la blockchain Bonkcoin et utilise la méthode de hachage Scrypt pour la preuve de travail (Proof of Work). Ce logiciel est adapté du Dogecoin Core, du Bitcoin Core et d'autres crypto-monnaies.

Pour plus d'informations sur les frais par défaut utilisés sur le réseau Bonkcoin, veuillez vous référer à [recommandation de frais](doc/fee-recommendation.md).

**Site web:** [bonkcoin.org](https://bonkcoin.org)

## Différences avec le Dogecoin

Bonkcoin est un fork du Dogecoin, conçu pour offrir une expérience similaire et familière.

Changements :

* Les adresses commencent par `P` au lieu de `D`
* Les fonctionnalités BIPS commenceront au bloc 1000
* AuxPow commence au bloc 100 000 (ID de chaîne : 63)
* L'interface graphique a été adaptée pour Bonkcoin

## Usage 💻

Pour commencer votre voyage avec Bonkcoin Core, consultez le [guide d'installation](INSTALL.md) et l'[introduction](doc/getting-started.md).

L'API JSON-RPC fournie par Bonkcoin Core est auto-documentée et peut être consultée avec `bonkcoin-cli help`, tandis que des informations détaillées pour chaque commande peuvent être consultées avec `bonkcoin-cli help <commande>`. Vous pouvez également consulter la [documentation Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) - qui met en œuvre un protocole similaire - pour obtenir une version consultable.

### Ports

Bonkcoin Core utilise par défaut le port `33874` pour la communication peer-to-peer 
qui est nécessaire pour synchroniser la blockchain du « mainnet » et rester informé 
des nouvelles transactions et des nouveaux blocs. De plus, un port JSONRPC peut être ouvert, 
qui est par défaut le port `33873` pour les nœuds du réseau principal. 
Il est fortement recommandé de ne pas exposer les ports RPC à l'internet public.

| Fonction | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33874 |   44874 |   18444 |
| RPC      |   33873 |   44873 |   18332 |

## Développement en cours 💻

Bonkcoin Core est un logiciel libre et communautaire. 
Le processus de développement est ouvert et visible publiquement ; 
tout le monde peut voir, discuter et travailler sur le logiciel

Principales ressources de développement :

* [GitHub Projects](https://github.com/bonkcoinppc/bonkcoin/projects) est utilisé pour
  suivre les travaux planifiés et en cours pour les prochaines versions.
* [GitHub Discussion](https://github.com/bonkcoinppc/bonkcoin/discussions) est utilisé pour discuter des fonctionnalités, des projets et des projets en cours.
  pour discuter des fonctionnalités, planifiées et non planifiées, liées à la fois au développement du
  développement du logiciel Bonkcoin Core, des protocoles sous-jacents et de l'actif BONC.  
* [BonkcoinDev subreddit](https://www.reddit.com/r/bonkcoindev/)

### Stratégie de version
Les numéros de version suivent la sémantique ```major.minor.patch```.

### Branches
Il y a 3 types de branches sur ce dépôt :

- **master:** Stable, contient la dernière version de la dernière version *major.minor*.
- **maintenance:** Stable, contient la dernière version des versions précédentes, qui sont toujours en maintenance active. Format : ```<version>-maint```
- **development:** Unstable, contient le nouveau code pour les versions planifiées. Format : ``<version>-maint`` : ``<version>-dev```

*Les branches Master et maintenance sont exclusivement mutables par version.*
*Les versions planifiées auront toujours une branche de développement *
*et les pull requests doivent être soumises sur celles-ci. Les branches de maintenance sont là pour **les corrections de bugs uniquement,***
*Veuillez soumettre les nouvelles fonctionnalités sur la branche de développement avec la version la plus élevée.*

## Contribuer 🤝

Si vous trouvez un bug ou si vous rencontrez des problèmes avec ce logiciel, 
veuillez le signaler [ici](https://github.com/bonkcoinppc/bonkcoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Veuillez consulter [le guide de contribution](CONTRIBUTING.md) pour savoir comment vous pouvez participer au développement de Bonkcoin Core. Il y a souvent des
[topics seeking help](https://github.com/bonkcoinppc/bonkcoin/labels/help%20wanted) où vos contributions auront un impact important et seront très appréciées.

## Communautés 🐸

Vous pouvez rejoindre les communautés sur différents médias sociaux pour voir ce qui se passe, 
rencontrer des gens et discuter, trouver le dernier mème, en savoir plus sur Bonkcoin, 
donner ou demander de l'aide, partager votre projet.

Voici quelques espaces à visiter :

* [r/Bonkcoin](https://www.reddit.com/r/bonkcoin/)
* [Discord](https://bonkcoin.org/discord)
* [Telegram](https://t.me/BonkcoinGroup)
* [Twitter/X](https://twitter.com/BonkcoinNetwork)

## Foire aux question ❓

Vous avez une question concernant Bonkcoin ? Une réponse se trouve peut-être déjà dans la [FAQ](doc/FAQ.md) ou dans la [section Q&A](https://github.com/bonkcoinppc/bonkcoin/discussions/categories/q-a) du forum de discussion !

## Licence ⚖️
Bonkcoin Core est publié sous les termes de la licence MIT. Voir
[COPYING](COPYING) pour plus d'informations ou voir
[opensource.org](https://opensource.org/licenses/MIT)

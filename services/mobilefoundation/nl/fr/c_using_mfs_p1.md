---

copyright:
  years: 2016

---

#	Utilisation du plan Developer
{: #using_mobilefoundation_p1}

Dernière mise à jour : 4 août 2016
{: .last-updated}

Une fois l'instance de service {{site.data.keyword.mobilefoundation_short}}: Developer créée, au bout de quelques secondes, vous pouvez accéder à la `Présentation` du site {{site.data.keyword.Bluemix_notm}} qui fournit des tutoriels et des vidéos facilitant
vos premiers pas avec le service {{site.data.keyword.mobilefoundation_short}}. 

## Démarrage du serveur {{site.data.keyword.mobilefirst}}
{: #start_mobilefoundation_p1}
* Pour démarrer le serveur
{{site.data.keyword.mfserver_short_notm}} avec les paramètres par
défaut, cliquez sur **Start Basic Server**.

Cette option affecte les paramètres suivants à un serveur {{site.data.keyword.mfserver_long_notm}} :
*	1 Go de mémoire. Cette taille est suffisante pour des activités de développement et des activités de test sommaires et pour des charges de travail à faible échelle.


*	Le `nom_d'utilisateur` et le `mot_de_passe` sont générés automatiquement pour vous. Vous pouvez y accéder une fois que le
serveur est en opération.

Le processus de mise à disposition commence. Ce processus prend environ 10 minutes et une fenêtre de
message indique la progression de l'opération. A son terme, un tableau de bord s'affiche et présente les éléments suivants :
*	L'état du serveur que vous exécutez (état, taille).

*	La route de serveur créée pour vous. Utilisez cette route dans votre application mobile pour vous connecter à {{site.data.keyword.mfserver_short_notm}}.

*	Votre `nom_d'utilisateur` personnel et votre `mot_de_passe`
pour accéder à la console {{site.data.keyword.mfp_oc_short_notm}}. Le
`mot_de_passe` est masqué. Cliquez sur l'icône **Show Password** pour le visualiser. 

*	Cliquez sur **Launch Console** pour lancer la
console {{site.data.keyword.mfp_oc_short_notm}}.


<!--This console runs inside the container.--> Elle vous permet de gérer vos
applications et périphériques mobiles, l'utilisation de votre serveur en tant
que serveur dorsal mobile, l'envoi de notifications push, etc.

## Re-création du serveur {{site.data.keyword.mobilefirst}}
{: #recreate_mobilefoundation_p1}

*	Cliquez sur **Recreate** pour re-créer le serveur.

* Cette action arrête votre serveur existant et supprime les données. Toutes les
données de votre serveur mobile sont perdues. Une
nouvelle instance de serveur est créée avec une version mise à jour, si elle est disponible. Cette action prend quelques minutes avant de s'achever.

##	Paramétrage d'une configuration avancée
{: #using_mfs_advanced_p1}

L'option **Start Server with Advanced Configuration**
de la page `Overview` permet de créer le serveur avec des
paramètres avancés ou personnalisés. Vous pouvez également mettre à jour les paramètres du serveur
pour personnaliser sa configuration en cliquant sur l'onglet **Configuration**. {{site.data.keyword.mobilefoundation_short}}
vous permet d'accéder à certains paramètres avancés.

*	Dans l'onglet **Topology**, vous pouvez sélectionner la taille du serveur, ainsi que le nombre d'instances dont vous avez besoin. Le serveur par défaut doté d'1 Go
est idoine pour le développement et des tests sommaires.

  - Sélectionnez la taille appropriée pour votre serveur compte tenu de
vos besoins.

* **Nodes** affiche le nombre de noeuds créés. Cette
zone n'est pas modifiable dans {{site.data.keyword.mobilefoundation_short}}: Developer. Par défaut, le nombre de noeuds <!--in your {{site.data.keyword.IBM_notm}} container group--> s'élève à **1** dans le plan Developer. 

Pour plus de détails, reportez-vous à la
[documentation
d'{{site.data.keyword.mobilefoundation_long}}](https://www.ibm.com/support/knowledgecenter/SSHS8R_8.0.0/wl_welcome.html){: new_window}.

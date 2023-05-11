# Projet_DSSS

Ce projet s'intéresse à l'étude de l'impact des conditions climatiques humides ou venteuses sur la consommation électrique dans les grandes métropoles françaises, et s'il existe un lien avec l'isolation thermique des ménages. 

En plus des données sur l'isolation thermiques délivrées par la FNAIM (répartition entre A et G des dépenses énergétiques par foyer par ville), ce projet utilise deux bases de données principales :
- L'ensemble des données climatiques quotidiennes de 119 stations météorologiques françaises du 1er janvier 2020 au 21 avril 2021. Il s'agit de la maille géographique la plus fine possible pour des données climatiques temporelles. La base de donnée étant libre d'accès, elle a été téléchargée en local. Elle regroupe des variables telles que la température maximale, minimale, moyenne, la hauteur des précipitations, l’humidité relative maximale, minimale, moyenne, la durée en minute sous 40\% d’humidité, au-dessus de 80\%, et pour finir la vitesse du vent moyenne en m/s : https://www.data.gouv.fr/fr/datasets/donnees-quotidiennes-de-119-stations-en-france-metropolitaine-pour-les-etudes-de-liens-entre-meteorologie-et-covid-19-du-01-01-2020-au-21-04-2021/
- L’ensemble des données de consommation électrique en MW de 21 grandes métropoles françaises. Elle est mesurée toutes les quinze minutes depuis 2019 : https://odre.opendatasoft.com/explore/dataset/eco2mix-metropoles-tr/information
- Les données relatives au logement de l'INSEE : https://www.insee.fr/fr/statistiques/5650749
- La base de données relatives aux DPE est manuellement crée depuis le baromètres des DPE de la FNAIM : https://www.fnaim.fr/4262-barometre-des-dpe-novembre-2022.htm (--> "télécharger le baromètre des DPE de la FNAIM dans son intégralité")

Afin de reproduire l'expérience, il suffit de télécharger et de lancer le fichier "code_dsss" en veillant à bien récupérer les bonnes bases de données (soit depuis les sites respectifs, soit depuis le sharepoint de l'ENSAE).

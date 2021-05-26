# Personal resume by Angular
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 



simple personal resume application created by Angular and Github pages.

 [Live Demo](https://simon-lepennec.github.io/cv)



## USAGE

#### 1 - clone the repository 

```shell
git clone https://github.com/Simon-LePennec/cv.git
```

you can also make a fork on your github account. 

#### 2 - installing the dependencies
```shell
cd cv 
npm install 
npm install -g angular-cli-ghpages
```

#### 3 - setting your personal data

for that, you have juste to edited the file _src/assets/data/perso.json_


 ```json
 {
    "profile": {
        "firstname": "Simon",
        "lastname": " Le Pennec ",
        "title": "Ingénieur en géomatique",
        "photo": "./assets/img/avataaars.png",
        "city": "Nantes",
        "phone": "",
        "mail": "slpennec@gmail.com",
        "summary": "Spécialisé dans le domaine de la géomatique après des études de géographie, je dispose d’une connaissance approfondie des outils de cartographie et de traitement d’images. Je maîtrise les technologies SIG Open Sources me permettant de les exploiter sur l’ensemble de la chaîne de traitement, de la manipulation et l’analyse de la donnée géographique à sa valorisation par la visualisation web."
    },
    "social": [
        {
            "name":"linkedin",
            "link":"https://www.linkedin.com/in/simon-le-pennec/",
            "icon":["fab","linkedin"]
        },
        {
            "name":"github",
            "link":"https://github.com/simon-lepennec/",
            "icon":["fab","github"]
        }
    ]
    ,
    "experiences": [{
            "company": "SGEvT",
            "picture": "https://media-exp1.licdn.com/dms/image/C560BAQGRClS0CmuLvA/company-logo_200_200/0?e=2159024400&v=beta&t=gZZTjAs11J7xvLuECcT6ZlVbBre8KvwSZSqaBLfV508",
            "location": "Toulouse",
            "title": "Ingénieur en géomatique",
            "period": "NOV 2017 - DEC 2020",
            "description": [
                "Développement d'indicateurs géographiques dans toutes les thématiques de l'aménagement du territoire pour l'aide à la décision de politiques publiques",
                "Développement de méthodologies de calculs d'indicateurs",
                "Automatisation des traitements sur la base de logiciels et librairies libres (Pyhton, SQL, R ...)",
                "Développement de la data-visualisation web de ces indicateurs",
                "Industrialisation des produits développés",
                "Suivi des missions clients dans la prestation de services de l'application TEREvAL"
            ]
        },
        {
            "company": "Gaz Éléctricité de Grenoble",
            "picture": "https://upload.wikimedia.org/wikipedia/commons/a/a1/Logo_GEG.jpg",
            "location": "Grenoble",
            "title": "Ingénieur en géomatique",
            "period": "MAR 2017 - SEP 2017",
            "description": [
                "Développement d'une plate-forme de cartographie en ligne pour l'aide à la prospection et l'implantation de projets éoliens, hydro-électriques, photovoltaïques, et de méthanisation.  Mise en place d'une infrastructure PostGIS-GeoServer-OpenLayers sur serveur CentOS, programmation HTML, PHP et JavaScript",
                "Création d’un module python QGis pour l'évaluation automatique de potentiel de puissance d'installations hydro-électrique selon la localisation des centrales"
            ]
        },
        {
            "company": "Véolia",
            "picture": "https://cdn.1min30.com/wp-content/uploads/2018/04/logo-Veolia.jpg",
            "location": "Rennes",
            "title": "Technicien SIG",
            "period": "MAI 2016 - AOU 2016",
            "description": [
                "Mise à jour du système d'information géographique à partir de plans de récolement réseaux issus de la DAO, à l’aide des solutions ArcGis, Autocad et FME",
                "Production de cartes thématiques"
            ]
        }
    ],
    "educations": [{
            "title": "Master Sciences Géomatiques en Environnement et Aménagement (SIGMA)",
            "city": "Toulouse",
            "degree": "Master",
            "period": "2016 - 2017",
            "university": "Université Toulouse, co-accrédité ENSAT",
            "picture": "https://seekvectorlogo.com/wp-content/uploads/2019/09/universite-federale-toulouse-midi-pyrenees-vector-logo-small.png"
        },
        {
            "title": "Licence Aménagement du territoire, Géographie, Environnement",
            "city": "Rennes",
            "degree": "Licence",
            "period": "2012 - 2015",
            "university": "Université Rennes II",
            "picture": "https://pbs.twimg.com/profile_images/1069527473635958784/MftAfLHn_400x400.jpg"
        }
    ],
    "skills": [
        {
            "name": "Python",
            "icon":["fab","python"]
        } , 
        {
            "name": "html",
            "icon":["fab","html5"]
        },
        {
            "name": "css",
            "icon":["fab","css3-alt"]
        } ,
        {
            "name": "Javascript",
            "icon":["fab","js"]
        }, 
        {
            "name": "Angular",
            "icon":["fab","angular"]
        } ,
        {
            "name": "php",
            "icon":["fab","php"]
        } ,
        {
            "name": "globe",
            "icon":["fas","globe-americas"]
        } ,
        {
            "name": "database",
            "icon":["fas","database"]
        } ,
        {
            "name": "R",
            "icon":["fab","r-project"]
        } ,
        {
            "name": "git",
            "icon":["fab","git-alt"]
        } ,
        {
            "name": "windows",
            "icon":["fab","windows"]
        } ,
        {
            "name": "linux",
            "icon":["fab","linux"]
        }
]
}
```

NB : for the skills part, you need to choose an icon from [Fontawesome's gallery](https://fontawesome.com/icons?d=gallery).


#### 4 - deploying the app on Github pages 

Github offers the possibility to host an angular application for free through the Github pages feature, and it's really simple by using the node package **angular-cli-ghpages**.

NB: you need to make a fork or a copy of the repository on your github account to be able to share the app on your github pages.


```shell
ng build --prod --base-href https://[username].github.io/[repo]/

ngh --no-silent
```

after that you can visit your personal page on **https://[username].github.io/[repo]**


#### 5 - Advanced use

```shell
ng serve
```

## Contributing

All bug reports and pull requests are welcome. 

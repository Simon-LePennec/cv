# Personal resume by Angular
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 



Simple personal resume application created by Angular and Github pages.

 [Live Demo](https://simon-lepennec.github.io/cv)



## USAGE

#### 1 - Clone the repository 

```shell
git clone https://github.com/Simon-LePennec/cv.git
```

You can also make a fork on your github account. 


#### 2 - Installing the dependencies
```shell
cd cv 
npm install 
npm install -g angular-cli-ghpages
```


#### 3 - Setting your personal data

For that, you have juste to edited the file _src/assets/data/perso.json_

NB : for the skills part, you need to choose an icon from [Fontawesome's gallery](https://fontawesome.com/icons?d=gallery).



#### 4 - Deploying the app on Github pages 

Github offers the possibility to host an angular application for free through the Github pages feature, and it's really simple by using the node package **angular-cli-ghpages**.

NB: you need to make a fork or a copy of the repository on your github account to be able to share the app on your github pages.


```shell
ng build --prod --base-href https://[username].github.io/[repo]/

ngh --no-silent
```

After that you can visit your personal page on **https://[username].github.io/[repo]**


#### 5 - Advanced use

```shell
ng serve
```

## Contributing

All bug reports and pull requests are welcome. 

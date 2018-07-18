# Loren's Notes


- npm install
- npm audit fix
- npm install -g npm (if suggested)
- npm run start

Now view at http://localhost:4200/

`npm run deploy:mock` to deploy to gp-pages.

resides at DirectoryBuilder/ngx-project.


This repo has this error, probably from copying grid (account to vehicles):

Error during template compile of 'SharedModule'
  Function calls are not supported in decorators but 'FlexLayoutModule' was called.


Frontend shared vehicle text page currently at:
https://github.com/DataPortal/dataportal.github.io


Tried the following, didn't work:
Changed from 4200 to 4201 in bs-config.json
ng serve --port 4201


SUMO = Awesome
https://github.com/xmlking/ngx-starter-kit
https://xmlking.github.io/ngx-starter-kit/home

Found at NGXS resources
https://ngxs.gitbook.io/ngxs/community/resources


home route:
libs/home/src/lib/containers/landing.component.html

Commented out "Get started" button.


Top Bar nav holder
libs/home/src/lib/components/header/header.component.html

Navigation in home resides here:
libs/home/src/lib/components/header/header.component.ts


Top Bar navigation paths
libs/home/src/lib/home.module.ts

Desktop navigation paths
apps/webapp/src/app/core/menu-data.ts

Dashboard navigation paths
libs/dashboard/src/lib/dashboard.module.ts


Commented out "Intro" link.

About - Changed title, added View Map button, removed Features button
libs/home/src/lib/containers/about/about.component.html


Accounts Grid List
libs/grid/src/lib/containers/accounts-grid-list

Vehicles Grid List
libs/vehicles/src/lib/containers/vehicles-grid-list


Displayed User data from random account service defined in:
libs/grid/src/lib/services/random-account.service.ts
https://randomuser.me/api/?seed=datauser&nat=us&exc=login,registered&results=100

Replaced sumo, sumo1, sumo2, sumo3 with datauser, datauser1, datauser2, datauser3

First time,
Copied accounts-grid-list to home...containers and renamed to vehicles.

Second time, copied "libs/grid" to "libs/gridmap"
Replaced Account with Vehicle, account with vehicle, including in file names.

Copied blog folder, renamed to coordmap.

Commented out SHARE and LIKE on users list sample
Commented out logo assets/img/logo_text.png and assets/img/logo_text_dark.png
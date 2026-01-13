# CAWebPublishing Template
This is the CAWebPublishing Template built with [handlebars](https://handlebarsjs.com/) and used by the CAWebPublishing Servce for static site generation.

## Using npm to start the website locally  

``` npm run install ```  
This command will install all the necessary npm packages to your local website directory.  

---

``` npm run serve ```  
This command will run the website in your [http://localhost:9000](http://localhost:9000) and watch for any changes made.  

---

``` npm run serve:audit ```  
This command does the same as `npm run serve` and will also generate a WordPress CSS Audit, IBM Accessibility Checker Report, and a JSHint Report page as well.  

---

## Changing colorscheme
Since this template utilizes the [@caweb/framework](https://github.com/CAWebPublishing/framework) and [@caweb/icon-library](https://github.com/CAWebPublishing/icon-library) you can change the scheme by running

` npm run serve:scheme:<color> ` - where \<color\> is one of the following:   
- none - *Note: this will disable the [@caweb/framework](https://github.com/CAWebPublishing/framework) and [@caweb/icon-library](https://github.com/CAWebPublishing/icon-library), only do this if providing your own frontend UI  
- delta
- eureka
- mono
- oceanside
- orangecounty
- pasorobles
- sacramento
- santabarbara
- santacruz
- shasta
- sierra
- trinity

## Output
All the web content is generated to the `/build/` folder.
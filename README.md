coderbits2pdf
=============

Create a pdf of your [Coderbits](https://coderbits.com) profile, with the option of listing any of your github repos.

Not on coderbits yet? Click [here](https://coderbits.com/account/signup?inviteCode=3a0c4738-12bb-4852-9c90-7bd2c4e2a46d) to join (invite link)

Usage -

    python coderbits2pdf --make username      # create resume
    python coderbits2pdf --add username       # add user
    python coderbits2pdf --del username       # delete user
    python coderbits2pdf --add-repo username  # add more repositories
    python coderbits2pdf --del-repo username  # delete repositories
    
To do -

 1. Improve design - better css and layout
 2. Create demo site.
 
Known issues -

 1. A repository might get cutoff in the pdf if it's at the bottom of the page. This is due to weesyprint's quirk that it can't page break

Requires -

 - [requests](http://docs.python-requests.org/en/latest/index.html)
 - [PyYaml](http://pyyaml.org/)
 - [WeasyPrint](http://weasyprint.org/)
 - [jinja2](http://jinja.pocoo.org)
 
Hattip -

 - [Bootstrap](http://twitter.github.com/bootstrap)

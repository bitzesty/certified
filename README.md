# Certified

Solves http://martinottenwaelter.fr/2010/12/ruby19-and-the-ssl-error/ by providing a crt bundle and explicitly telling Ruby where to find it. Also forces `OpenSSL::SSL::VERIFY_PEER`

In your Gemfile add:

``` Ruby
gem 'certified', github: 'bitzesty/certified', branch: 'master'
```

# my_app_padrino
Sample app using Padrino Framework


Installation:

gem install padrino

Github repo for Padrino

https://github.com/padrino/padrino-framework

Initial steps of generating the project

padrino g project myapp -d datamapper

cd myapp

bundle install

padrino start

=> Padrino/0.13.3.3 has taken the stage development at http://127.0.0.1:3000
[2017-01-27 16:10:43] INFO  WEBrick 1.3.1
[2017-01-27 16:10:43] INFO  ruby 2.3.0 (2015-12-25) [x86_64-darwin15]
[2017-01-27 16:10:43] INFO  WEBrick::HTTPServer#start: pid=1820 port=3000

Then, type the below code(s) in the app.rb file for the sample output

    get '/' do
        "Hello World"
    end


    get '/hi' do
        "Hey everyone!!!"
    end



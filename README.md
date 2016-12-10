# RubyonRails
Installation notes

First install the rails by downloading from rails installer.org

The install the downloaded file.

If you try to install it then you would be getting a gem error and to remove that error we need to http://guides.rubygems.org/ssl-certificate-update/#
where we can get the necessary instructions to make it right.

Once you completed the above the you are good to go to run the server.

After you have run the server, when you will create the new controller and view then you will not be able to load the new file and get an internal
500 server error. In that case you have to follow the following 
In your /app/views/layouts/application.html.erb lines 5 and 6, change the first parameter from application to default.

I met the same problem, too for my situation, I don't know why, but it only happens on Windows. The parameter application works on the web server.

Then you are good to use your own server.

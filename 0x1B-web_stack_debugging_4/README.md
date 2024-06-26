# Web Stack Debugging

This project contains tasks for learning about how to debug web stacks.

## Tasks...

+ [x] 0. Sky is the limit, let's bring that limit higher<br/>_**[0-the_sky_is_the_limit_not.pp](0-the_sky_is_the_limit_not.pp)**_ contains a Puppet manifest that improves the capabilities of an Nginx server.
  + Info:
    + In this web stack debugging task, we are testing how well our web server setup featuring Nginx is doing under pressure and it turns out it’s not doing well: we are getting a huge amount of failed requests.
    + For the benchmarking, we are using ApacheBench which is a quite popular tool in the industry. It allows you to simulate HTTP requests to a web server. In this case, I will make 2000 requests to my server with 100 requests at a time. We can see that 943 requests failed, let’s fix our stack so that we get to 0, and remember that when something is going wrong, logs are your best friends!

+ [x] 1. User limit<br/>_**[1-user_limit.pp](1-user_limit.pp)**_ contains a Puppet manifest that changes the OS configuration so that it is possible to login with the `holberton` user and open a file without any error message.

Strapdown on Heroku with Rack
====

[Strapdown](https://github.com/arturadib/strapdown
) is an awesome tool that makes it embarrassingly simple to create elegant Markdown documents. You can serve it directly from [strapdownjs.com](http://strapdownjs.com) like this:

    <script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>

But, if you would like to use it on an https site, that won't work.
This simple rack app makes it possible to serve strapdown on [Heroku](https://www.heroku.com/), and use piggyback SSL to serve it from an https domain.

A sample application is running on [http://strapdown.herokuapp.com](http://strapdown.herokuapp.com), so you can include this from an https domain with

    <script src="https://strapdown.herokuapp.com/v/0.2/strapdown.js"></script>
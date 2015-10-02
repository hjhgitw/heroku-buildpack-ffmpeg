Heroku buildpack: FFMpeg
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for using [ffmpeg](http://www.ffmpeg.org/) in your project.  

Usage
-----

    $ heroku buildpacks:add https://github.com/tastemade/heroku-buildpack-ffmpeg

You can verify installing ffmpeg by following command.

    $ heroku run "ffmpeg -version"

Hacking
-------
If you want to use your own ffmpeg binary, fork and rewrite following line.

https://github.com/tastemade/heroku-buildpack-ffmpeg/blob/master/bin/compile#L10

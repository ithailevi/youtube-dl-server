
# youtube-dl-server

Allows you to download mp3 or mp4 from popular video sites. You can use bookmarklets or Chrome extension to initiate download.

## Usage

    $ youtube-dl-server

### API
	
	http://localhost:9099/?music=<url>  Download and convert to mp3 
	http://localhost:9099/?video=<url>  Download and convert to iPad video
 
## Installation

	$ sudo apt-get install ffmpeg 
    $ sudo wget --no-check-certificate https://github.com/dz0ny/youtube-dl/raw/master/youtube-dl -O /usr/local/bin/youtube-dl && sudo chmod a+x /usr/local/bin/youtube-dl
    $ curl https://github.com/dz0ny/youtube-dl-server/raw/master/install.sh | sh

# License 

(The MIT License)

Copyright (c) 2011 Janez Troha <janez.troha@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
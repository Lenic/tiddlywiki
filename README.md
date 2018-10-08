# tiddlywiki

TiddlyWiki 5 Docker image. You can use it by follow command:

```
docker run -d --name tiddlywiki -v <your-wiki-path>:/data -p 8080:8080 lenic/tiddlywiki
```

## Configurable Variables

The default variable of env.

```
ENV TW_PORT=8080 \
  TW_ROOTTIDDLER=$:/core/save/all \
  TW_RENDERTYPE=text/plain \
  TW_SERVETYPE=text/html \
  TW_USERNAME="" \
  TW_PASSWORD="" \
  TW_HOST=0.0.0.0 \
  TW_PATHPREFIX=""
```

The alternative scheme is replace the default command.

## Author

Lenic <lenic@live.cn>.

## License

MIT License

Copyright (c) 2018 Lenic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

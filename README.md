# You-Get

[![PyPI version](https://img.shields.io/pypi/v/you-get.svg)](https://pypi.python.org/pypi/you-get/)
[![Build Status](https://travis-ci.org/soimort/you-get.svg)](https://travis-ci.org/soimort/you-get)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/soimort/you-get?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[You-Get](https://you-get.org/) is a tiny command-line utility to download media contents (videos, audios, images) from the Web, in case there is no other handy way to do it.

change the introduction for develop useage

## Installation

### Prerequisites

The following dependencies are required and must be installed separately, unless you are using a pre-built package or chocolatey on Windows:

* **[Python 3](https://www.python.org/downloads/)**
* **[FFmpeg](https://www.ffmpeg.org/)** (strongly recommended) or [Libav](https://libav.org/)
* (Optional) [RTMPDump](https://rtmpdump.mplayerhq.hu/)

### Option 5: Git clone

This is the recommended way for all developers, even if you don't often code in Python.

```
$ git clone git://github.com/soimort/you-get.git
```

Then put the cloned directory into your `PATH`, or run `./setup.py install` to install `you-get` to a permanent path.

## Supported Sites

| Site | URL | Videos? | Images? | Audios? |
| :--: | :-- | :-----: | :-----: | :-----: |
| **YouTube** | <https://www.youtube.com/>    |✓| | |
| **Twitter** | <https://twitter.com/>        |✓|✓| |
| VK          | <http://vk.com/>              |✓|✓| |
| Vine        | <https://vine.co/>            |✓| | |
| Vimeo       | <https://vimeo.com/>          |✓| | |
| Vidto       | <http://vidto.me/>            |✓| | |
| Videomega   | <http://videomega.tv/>        |✓| | |
| Veoh        | <http://www.veoh.com/>        |✓| | |
| **Tumblr**  | <https://www.tumblr.com/>     |✓|✓|✓|
| TED         | <http://www.ted.com/>         |✓| | |
| SoundCloud  | <https://soundcloud.com/>     | | |✓|
| SHOWROOM    | <https://www.showroom-live.com/> |✓| | |
| Pinterest   | <https://www.pinterest.com/>  | |✓| |
| MusicPlayOn | <http://en.musicplayon.com/>  |✓| | |
| MTV81       | <http://www.mtv81.com/>       |✓| | |
| Mixcloud    | <https://www.mixcloud.com/>   | | |✓|
| Metacafe    | <http://www.metacafe.com/>    |✓| | |
| Magisto     | <http://www.magisto.com/>     |✓| | |
| Khan Academy | <https://www.khanacademy.org/> |✓| | |
| Internet Archive | <https://archive.org/>   |✓| | |
| **Instagram** | <https://instagram.com/>    |✓|✓| |
| InfoQ       | <http://www.infoq.com/presentations/> |✓| | |
| Imgur       | <http://imgur.com/>           | |✓| |
| Heavy Music Archive | <http://www.heavy-music.ru/> | | |✓|
| **Google+** | <https://plus.google.com/>    |✓|✓| |
| Freesound   | <http://www.freesound.org/>   | | |✓|
| Flickr      | <https://www.flickr.com/>     |✓|✓| |
| FC2 Video   | <http://video.fc2.com/>       |✓| | |
| Facebook    | <https://www.facebook.com/>   |✓| | |
| eHow        | <http://www.ehow.com/>        |✓| | |
| Dailymotion | <http://www.dailymotion.com/> |✓| | |
| CBS         | <http://www.cbs.com/>         |✓| | |
| Bandcamp    | <http://bandcamp.com/>        | | |✓|
| AliveThai   | <http://alive.in.th/>         |✓| | |
| interest.me | <http://ch.interest.me/tvn>   |✓| | |
| **755<br/>ナナゴーゴー** | <http://7gogo.jp/> |✓|✓| |
| **niconico<br/>ニコニコ動画** | <http://www.nicovideo.jp/> |✓| | |
| **163<br/>网易视频<br/>网易云音乐** | <http://v.163.com/><br/><http://music.163.com/> |✓| |✓|
| 56网     | <http://www.56.com/>           |✓| | |
| **AcFun** | <http://www.acfun.tv/>        |✓| | |
| **Baidu<br/>百度贴吧** | <http://tieba.baidu.com/> |✓|✓| |
| 爆米花网 | <http://www.baomihua.com/>     |✓| | |
| **bilibili<br/>哔哩哔哩** | <http://www.bilibili.com/> |✓| | |
| Dilidili | <http://www.dilidili.com/>     |✓| | |
| 豆瓣     | <http://www.douban.com/>       |✓| |✓|
| 斗鱼     | <http://www.douyutv.com/>      |✓| | |
| Panda<br/>熊猫 | <http://www.panda.tv/>      |✓| | |
| 凤凰视频 | <http://v.ifeng.com/>          |✓| | |
| 风行网   | <http://www.fun.tv/>           |✓| | |
| iQIYI<br/>爱奇艺 | <http://www.iqiyi.com/> |✓| | |
| 激动网   | <http://www.joy.cn/>           |✓| | |
| 酷6网    | <http://www.ku6.com/>          |✓| | |
| 酷狗音乐 | <http://www.kugou.com/>        | | |✓|
| 酷我音乐 | <http://www.kuwo.cn/>          | | |✓|
| 乐视网   | <http://www.le.com/>           |✓| | |
| 荔枝FM   | <http://www.lizhi.fm/>         | | |✓|
| 秒拍     | <http://www.miaopai.com/>      |✓| | |
| MioMio弹幕网 | <http://www.miomio.tv/>    |✓| | |
| 痞客邦   | <https://www.pixnet.net/>      |✓| | |
| PPTV聚力 | <http://www.pptv.com/>         |✓| | |
| 齐鲁网   | <http://v.iqilu.com/>          |✓| | |
| QQ<br/>腾讯视频 | <http://v.qq.com/>      |✓| | |
| 企鹅直播 | <http://live.qq.com/>          |✓| | |
| Sina<br/>新浪视频<br/>微博秒拍视频 | <http://video.sina.com.cn/><br/><http://video.weibo.com/> |✓| | |
| Sohu<br/>搜狐视频 | <http://tv.sohu.com/> |✓| | |
| **Tudou<br/>土豆** | <http://www.tudou.com/> |✓| | |
| 虾米     | <http://www.xiami.com/>        | | |✓|
| 阳光卫视 | <http://www.isuntv.com/>       |✓| | |
| **音悦Tai** | <http://www.yinyuetai.com/> |✓| | |
| **Youku<br/>优酷** | <http://www.youku.com/> |✓| | |
| 战旗TV   | <http://www.zhanqi.tv/lives>   |✓| | |
| 央视网   | <http://www.cntv.cn/>          |✓| | |
| 花瓣     | <http://huaban.com/>           | |✓| |
| Naver<br/>네이버 | <http://tvcast.naver.com/>     |✓| | |
| 芒果TV   | <http://www.mgtv.com/>         |✓| | |
| 火猫TV   | <http://www.huomao.com/>         |✓| | |
| 全民Tv   | <http://www.quanmin.tv/>         |✓| | |

For all other sites not on the list, the universal extractor will take care of finding and downloading interesting resources from the page.

### Known bugs

If something is broken and `you-get` can't get you things you want, don't panic. (Yes, this happens all the time!)

Check if it's already a known problem on <https://github.com/soimort/you-get/wiki/Known-Bugs>, and search on the [list of open issues](https://github.com/soimort/you-get/issues). If it has not been reported yet, open a new issue, with detailed command-line output attached.

## Getting Involved

You can reach us on the Gitter channel [#soimort/you-get](https://gitter.im/soimort/you-get) (here's how you [set up your IRC client](http://irc.gitter.im) for Gitter). If you have a quick question regarding `you-get`, ask it there.

All kinds of pull requests are welcome. However, there are a few guidelines to follow:

* The [`develop`](https://github.com/soimort/you-get/tree/develop) branch is where your pull request should go.
* Remember to rebase.
* Document your PR clearly, and if applicable, provide some sample links for reviewers to test with.
* Write well-formatted, easy-to-understand commit messages. If you don't know how, look at existing ones.
* We will not ask you to sign a CLA, but you must assure that your code can be legally redistributed (under the terms of the MIT license).

## Legal Issues

This software is distributed under the [MIT license](https://raw.github.com/soimort/you-get/master/LICENSE.txt).

In particular, please be aware that

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Translated to human words:

*In case your use of the software forms the basis of copyright infringement, or you use the software for any other illegal purposes, the authors cannot take any responsibility for you.*

We only ship the code here, and how you are going to use it is left to your own discretion.

## Authors

Made by [@soimort](https://github.com/soimort), who is in turn powered by :coffee:, :pizza: and :ramen:.

You can find the [list of all contributors](https://github.com/soimort/you-get/graphs/contributors) here.

# image-dl

## Installation

```bash
composer require maxvtest/image-dl:~1.0
```
## Usage

```PHP
use Maxvtest\ImageDl\ImageDl;

$url = 'http(s)://free-awesome-images.net/path/name.jpg';
$name = '/path/to/new-file.jpg';

$imageDl = new ImageDl;
$imageDl->sslVerifyPeer = true; // 'true' to download image from https, but without SSL verification.
$imageDl->download($url, $name);
```

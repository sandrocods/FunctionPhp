### Function PHP

## Usage

```
// include func.php in your php project
include 'func.php';
```

## Function Reference
* [Curl()](#Curl)
* [GetVarFromUser()](#GetVarFromUser)
* [Save](#Save)
* [Dot Trick](#Dot)
* [Random](#Random)
* [Get Between](#GetBetween)
* [Get String](#GetStr)
* [Name Generator](#NameGenerator)
* [Random Colors](#randomColors)
* [Readable Random String](#ReadableRandomString)
* [Rupiah](#Rupiah)
* [Generate Device ID](#GenDeviceId)
* [Warna](#Warna)
* [Random Name](#RandomName)
* [Generator UUID](#GenUUID)
* [Send Msg Telegram](#SendMSGTele)
* [Get Temporay Mail v1](#GetTemporaryMailv1)
* [View Temporay Mail v1](#ViewTemporaryMailv1)
* [Get Temporay GMail v1](#GetTemporaryGMailv1)
* [View Temporay GMail v1](#GetTemporaryMailv1)

### Curl()
  ```php
  $curl = curl($url , $method, $postfields, $followlocation, $headers );
  ```
  > Curl Website Response ( HttpCode , Header, Body, $cookies )
  - `Url`: A `Your Url to curl`
  - `Method`: A `POST/GET`
  - `Postfields`: A `Your Postdata`
  - `Followlocation`: A `1/null`
  - `Headers`: A `array()`

### GetVarFromUser()
  ```php
  $input = GetVarFromUser('Text '); 
  ```
> Return Text input php

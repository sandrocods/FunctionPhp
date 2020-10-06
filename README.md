### Function PHP

## Usage

```
// include func.php in your php project
include 'func.php';
```

## Function Reference
* [Curl()](#Curl)
* [GetVarFromUser()](#GetVarFromUser)
* [Save()](#Save)
* [Dot()](#Dot)
* [Random()](#Random)
* [GetBetween()](#GetBetween)
* [GetString()](#GetStr)
* [NameGenerator()](#NameGenerator)
* [RandomColors()](#randomColors)
* [ReadableRandomString()](#ReadableRandomString)
* [Rupiah()](#Rupiah)
* [GenerateDeviceID()](#GenDeviceId)
* [Warna()](#Warna)
* [RandomName()](#RandomName)
* [GeneratorUUID()](#GeneratorUUID)
* [SendMsgTelegram()](#SendMsgTelegram)
* [GetTemporayMailv1()](#GetTemporaryMailv1)
* [ViewTemporayMailv1()](#ViewTemporaryMailv1)
* [GetTemporayGMailv1()](#GetTemporaryGMailv1)
* [ViewTemporayGMailv1()](#GetTemporaryMailv1)

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

### Save()
  ```php
  Save('name_file.txt',$value)
  ```
> Save to a file

### Dot()
  ```php
  $dot = dot($var);
  ```
- `$var`: A `String to dottrick`

### Random()
  ```php
  $rand = random($length, $a)
  ```
- `$length`: A `length your string`
- `$a`: A `0 = numeric / 1 = numeric + alphabet`

### GetBetween()
  ```php
  $get = get_between($string, $start, $end);
  ```
- `$string`: A `your string`
- `$start`: A `prefix your string to search`
- `$end`: A `suffix your stirng to search`

### getStr()
  ```php
  $get = getStr($string, $start, $end)
  ```
- `$string`: A `your string`
- `$start`: A `prefix your string to search`
- `$end`: A `suffix your stirng to search`


### NameGenerator()
  ```php
  $name = namegenerator();
  ```
> Return String name


### RandomColors()
  ```php
  $name = RandomColors();
  ```
> Return Color to your string

### ReadableRandomString()
  ```php
  $read = ReadableRandomString($length);
  ```
> Return Readable string
- `$length`: A `Length string`

### Rupiah()
  ```php
  $rupiah = Rupiah($value)
  ```
> Return number to rupiah currency
- `$value`: A `number string`

### ReadableRandomString()
  ```php
  $read = ReadableRandomString($length);
  ```
> Return Readable string
- `$length`: A `Length string`

### GenerateDeviceID()
  ```php
  $dev = GenerateDeviceID()
  ```
> Return Device id 

### Warna()
  ```php
  echo warna($text,'CYAN')
  ```
> Return Text with collor
- `$text`: A `Text string`
- `CYAN`: A `Collor`

### RandomName()
  ```php
  echo RandomName();
  ```
> Return Random Name From API

### GeneratorUUID()
  ```php
  echo GeneratorUUID()
  ```
> Return UUID From UUID


### SendMsgTelegram()
  ```php
  $send = send_telegram($chatid, $msg, $bottoken)
  ```
> Send Text to telegram
- `$chatid`: A `Chatid Your Bot`
- `$msg`: A `Your Msg TEXT`
- `$bottoken`: A `Bottoken Your bot`


### GetTemporayMailv1()
  ```php
  $get_email = Get_tempm($site)
  ```
> Get Email From API Generatoremail & Tempm
- `$site`: A `1 = generator.email / 2= tempm.com`
> Return array("email","name","domain","site"); 

### ViewTemporayMailv1()
  ```php
  $get = Read_tempm($site , $name, $domain);
  ```
> Return Result Generator Email
- `$site`: A `Get Site Value GetTemporayMailv1() `
- `$name`: A `Get Return Data from GetTemporayMailv1() `
- `$domain`: A `Get Return Data from GetTemporayMailv1() `

### GetTemporayGMailv1()
  ```php
  $get = gmailnator();
  ```
> Return Text with collor
-   return array('Response','Email','Token');

### ViewTemporayGMailv1()
  ```php
  $get = Read_gmailnator($token,$email)
  ```
> Return Result Email
- `$token`: A `Get Token Value GetTemporayGMailv1() `
- `$email`: A `Get Return Data from GetTemporayGMailv1() `

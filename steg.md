---
layout: default
published: true
---

# پنهان نگاری

## وبسایت های کاربردی

| آدرس | توضیح |
| :--- | :--- |
| https://secsy.net/easy_stegoCTF | ابزار های steganography |
| https://www.branah.com/braille-translator | مترجم خط Braille |
| http://bigwww.epfl.ch/demo/ip/demos/FFT/ | رمز گشایی TTF |
| https://www.dcode.fr/brainfuck-language | مترجم brainfuck |
| https://www.boxentriq.com/code-breaking/morse-code | مترجم morse code |
| https://georgeom.net/StegOnline/image | نمایش حالت LSB HALF |


## استخراج فایل در داخل فایل

```text
steghide info <filename> -p <password>
steghide extract -sf <filename> -p <password>
```

## اسختراج فایل در داخل فایل wav

```text
java -jar turgen.jar
```

## تبدیل کد های باینری به qrcode

```text
https://www.dcode.fr/binary-image
https://online-barcode-reader.inliteresearch.com/
```

## transformations عکس ها

```text
java -jar Stegsolve.jar
```

## بررسی فایل

```text
binwalk -e <file>
strings <file>
```

## حدس کلمه عبور فایل در فایل

```text
./steg_brute.py -b -d /usr/share/wordlists/rockyou.txt -f ../meow.wav
```

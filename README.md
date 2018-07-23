# snowboyWithGoogleStt<br>

## 스노우보이와 구글SST 사용
## 참고: https://github.com/chandong83/googleSpeech_with_NaverTTS
## 추후 과제: 네이버 tts대신에 구글스피치의 tts를 이용하여 대답을 문자에서 speech로 변환시키기

Support
===

Machine
------

> armv7l - Support (Raspberry Pi3)<br>

python version
------
>  python3.x - Support<br>

requirement
===

<pre>
<code>
$ sudo apt-get install swig
$ sudo apt-get install python-pyaudio python3-pyaudio sox
$ sudo apt-get install libatlas-base-dev
$ sudo apt-get install portaudio19-dev
$ sudo apt-get install python-dev
$ pip install pyaudio
</code>
</pre>


for Sample Test
===
##snowboy설치하기
##[url] https://blog.naver.com/rose1216_/221318052590

<pre>
<code>
$ cd snowboyWithGoogleStt

$ python3 googleSpeechWithSnowboy.py
</code>
</pre>
===

#example
<iframe width="640" height="360" src="https://www.youtube.com/GD71CLPCUjo" frameborder="0" gesture="media" allowfullscreen=""></iframe>
===

<pre>
you can say 'snowboy'
then snowboy is stopped and displayed to  'Hi, I am here!'
snowboy will start again after 5sec.
</pre>

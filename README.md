# LANnouncer-examples-curl

Curl examples for [LANnouncer](https://play.google.com/store/apps/details?id=com.keybounce.lannouncer&hl=en)

## Say something

`curl "http://192.168.1.77:1035/?SPEAK=hello there, I'm not alexa. I'm much better&@DONE@"`

## Start strobe

`curl "http://192.168.1.77:1035/?FLASH=CONTINUOUS@DONE@"`

## Stop strobe

`curl "http://192.168.1.77:1035/?FLASH=STOP@DONE@"`

## Play Chime

`curl "http://192.168.1.77:1035/?ALARM=CHIME&@DONE@"`

## Play Siren

`curl "http://192.168.1.77:1035/?ALARM=SIREN&@DONE@"`

## Sound Alarm

`curl "http://192.168.1.77:1035/?ALARM=ALARM&@DONE@"`

## Sound Doorbell

`curl "http://192.168.1.77:1035/?ALARM=DOORBELL&@DONE@"`

## Take a photo and return it

`curl "http://192.168.1.77:1035/?PHOTO=BACK&STSHRINK=TRUE&@DONE@"`

## Take a video and store it on the phone

`curl "http://192.168.1.77:1035/?VIDEO=10"`

## Play Chime - Remote execution (GCM enabled)

`curl "http://lannouncer.keybounce.com:1036/command?userName=MY_ID@gmail.com&deviceName=MY_DEVICE&command=ALARM%3DCHIME"`

## Take photo - Remote execution

`curl "http://lannouncer.keybounce.com:1036/command?userName=MY_ID@gmail.com&deviceName=MY_DEVICE&command=PHOTO%3DBACK%26STSHRINK%3DTRUE%26%40DONE%40"`


# LANnouncer-examples-curl

Curl examples for [LANnouncer](https://play.google.com/store/apps/details?id=com.keybounce.lannouncer&hl=en)

## Say something

`curl "http://192.168.1.77:1035/?SPEAK=hello there, I'm not alexa. I'm much better&@DONE@"`

## Start strobe

`http://192.168.1.77:1035/?FLASH=CONTINUOUS@DONE@`

## Stop strobe

`http://192.168.1.77:1035/?FLASH=STOP@DONE@`

## Play Chime

`curl http://192.168.1.77:1035/?ALARM=CHIME&@DONE@`

## Play Siren

`curl http://192.168.1.77:1035/?ALARM=SIREN&@DONE@`

## Sound Alarm

`curl http://192.168.1.77:1035/?ALARM=ALARM&@DONE@`

## Sound Doorbell

`curl http://192.168.1.77:1035/?ALARM=DOORBELL&@DONE@`

## Take a photo and return it

`curl 192.168.1.77:1035/?PHOTO=BACK&STSHRINK=TRUE&@DONE@`

## Take a video and store it on the phone

`curl 192.168.1.77:1035/?VIDEO=10`

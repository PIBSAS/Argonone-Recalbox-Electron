# Argonone-Recalbox-Electron Thanks to Pitch64
A fix to get working, Off Button and fan cooler working in Recalbox 8

Pitch64: https://forum.recalbox.com/topic/25351/recalbox-8-0-beta/2

</p>
<p align="center">
<img src="https://raw.githubusercontent.com/PIBSAS/RetroPieBios/master/logov3.png" alt="Raspberry Pi Buenos Aires" width="400" height="500"><img src="https://github.com/PIBSAS/Argonone-Recalbox-Electron/blob/main/logocase.png" alt="Raspberry Pi Buenos Aires" width="400" height="500">
</p>

# Instructions:

Power on Recalbox, once booted press `F4` then `ALT+F2`.

Login with:

`root`

`recalboxroot` You can't see what are you typing, so be precise or retry till you get sucess.

Once logged type:

`cd /`

Then this line without errors:

```
curl -sSL https://raw.githubusercontent.com/PIBSAS/Argonone-Recalbox-Electron/master/argonone-Recalbox-Electron-by-Pitch64.sh | bash
```

You will see the smBus error, don't worry is normal and will be fix it after reboot.Now press `Enter`and type:

```
argonone-config
```

Answer `Y` then `2` and put in numbers the minimum, medium and high temperature to make the fan works.

By default came with an example for:

1st temp: `55`

2nd temp: `60`

3rd temp: `65`

Done! Now type:

`reboot`

And all will works!!!

NOTE: You can make this from your Android phone/PC/Iphone/Another Raspberry Pi with any SSH program. So you can just copy and paste the long curl line.

<h1 align="center"> Invite a Coffee</h1>
<p align="center">
<a href="https://www.paypal.com/paypalme/RaspberryPiBsAs">
<img src="https://raw.githubusercontent.com/PIBSAS/MiPiTV/master/Paypal_2014_logo.png" alt="Invite a Coffee" width="40" height="50">
</a>
<a href="https://link.mercadopago.com.ar/raspberrypibsas">
<img src="https://raw.githubusercontent.com/PIBSAS/MiPiTV/master/MercadoPago.png" alt="Invite a Coffee" width="40" height="50">
</a>
</p>

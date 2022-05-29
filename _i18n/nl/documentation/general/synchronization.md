{% capture img-devices %} {% include image.html alt="

toestellen

       "

loc="/assets/images/documentation" file="gpodder-devices.png" %} {% endcapture
%}

{% capture img-synchronize %} {% include image.html alt="

synchroniseren

       "

loc="/assets/images/documentation" file="gpodder-synchronize.png" %} {%
endcapture %}

AntennaPod currently supports two synchronization options: via [gpodder.net](https://gpodder.net/)
and the [gPodder Sync app for Nextcloud](https://apps.nextcloud.com/apps/gpoddersync).

On gpodder.net anyone can create an account relatively easily and the service is
free to use. Unfortunately the service has large numbers of users, limited
funding and a lack of volunteer contributions. This means the server often is
overloaded, leading to errors in AntennaPod. If possible, we therefore recommend
that you use an existing account on a Nextcloud instance or start self-hosting
either gpodder.net or Nextcloud.

## gPodder Sync app for Nextcloud

If you have a Nextcloud account, install the gPodder Sync app or ask your server
admin to do so. Once that is installed, simply go to `Settings` »
`Synchronization` in AntennaPod, choose the relevant provider and enter the
server address.

## gpodder.net & your own gpodder server

- Create an account on gpodder.net or log in if you have one already.

   - Het advies is om met een account een toestel aan te maken op
gpodder.net/devices/ voor elke client die je gebruikt:<br />{{ img-devices | strip }}

   - Koppel de toestellen, na het aanmaken, met de "Configure" knop. Op deze manier
houdt gpodder.net automatisch de abonnementen van beide toestellen
gesynchroniseerd.<br />{{ img-synchronize | strip }}
- Then go to AntennaPod's `Settings` » `Synchronization`. There you can log in
to gpodder.net or even provide an alternative server if you want to host it
yourself. During login, AntennaPod asks what device you are currently logged
into. Select your newly created device.

*Did you create a device while logging in, rather than in advance as suggested
above?* Then be sure to press the `Force sync` button in AntennaPod to upload
the played state of all the episodes you listened to earlier. If you don't do
this, only podcasts that were added **after** linking the devices are
synchronized. There is an [open issue for gpodder.net](https://github.com/gpodder/mygpo/issues/388)
that requests to change the behavior.
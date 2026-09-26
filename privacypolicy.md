# Privacy Policy — Media Gallery Viewer

**Effective date:** 26 September 2026
**App:** Media Gallery Viewer for Android (`com.dukecorp.mediagalleryviewer`)
**Developer:** Bancha Setthanan

Media Gallery Viewer lets you browse, organise and upload photos and videos on a media server
that **you host and control**, such as a computer on your home network. This policy explains what
the app does with your information.

## Summary

- The developer **does not collect, store or receive** any of your personal data.
- The app has **no accounts, analytics, advertising, crash reporting or tracking**.
- The app talks **only to the server address you enter** in its Settings.
- Nothing is sold or shared with third parties.

## Information the app handles

### Media on your server
The app loads photos, videos, thumbnails, file details (such as file name, size, dimensions and
date taken), and camera metadata (such as camera model, exposure settings and, if present, the GPS
location recorded in the photo) from the server you configure. It shows this information on your
device. It is not sent anywhere else.

When you choose "Open in Maps" for a photo that has a location, the photo's coordinates are passed
to the maps app you pick on your device. The app never reads your device's own location.

### Photos and videos you upload
When you choose to upload, you pick items with Android's system photo picker. The app can only
access the items you select, and it sends them only to your configured server. The app does not
request permission to read your photo library.

### Changes you make
Actions such as marking favourites, creating albums, deleting or restoring items are sent to your
configured server so it can update your library.

### Settings stored on your device
The app stores its settings locally on your device: the server address, display preferences, and
Wake-on-LAN details (the server's hardware MAC address, IP address and port). These never leave
your device except as described under Wake-on-LAN below.

### Cached files
To load faster, the app keeps a cache of thumbnails and images on your device. When you share an
item, the original file is temporarily downloaded to the app's cache so it can be passed to the app
you choose in Android's share sheet. You can clear the image cache in **Settings → Clear Image Cache**,
and Android may clear the cache at any time.

### Wake-on-LAN
If Wake-on-LAN is enabled and your server does not respond, the app sends a small "magic packet"
on your local network to the addresses you configured, to wake the server. The packet contains
only the server's MAC address.

## Permissions

| Permission | Why it's needed |
|---|---|
| Internet (`INTERNET`) | To connect to your media server and send Wake-on-LAN packets. |
| Network state (`ACCESS_NETWORK_STATE`) | To check network connectivity. |

## Third parties

The app contains no third-party analytics, advertising or tracking software. It uses open-source
libraries only to display images, play video and make network connections, and those libraries
don't send your data to anyone. Your data goes only to the server you configure. That server is
operated by you or by whoever runs it for you, and its handling of data is up to its operator.

## Security

The app supports encrypted HTTPS connections to your server. You can choose plain HTTP, or allow a
self-signed certificate for your own server, in Settings. Those options are less secure and are
meant only for trusted home networks.

## Data retention and deletion

The developer holds no data about you, so there is nothing to request or delete from the developer.
Uninstalling the app, or clearing its storage in Android Settings, removes all settings and cached
files from your device. Media and library data on your server are controlled by the server's operator.

## Children

The app is not directed at children and does not knowingly collect information from anyone.

## Changes to this policy

If this policy changes, the updated version will be published at the same address with a new
effective date.

## Contact

Questions about this policy: **dukebkk@gmail.com**

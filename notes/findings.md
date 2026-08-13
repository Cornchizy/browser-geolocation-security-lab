# Lab Findings

## Browser Geolocation

This lab demonstrated how browser-based geolocation works. The browser requests permission before providing precise location information to a website.

## Location Permission Testing

The location permission prompt showed that users can choose whether to allow or block access to their location.

When permission is allowed, the browser can provide location information using the device's available location services.

When permission is blocked, precise browser geolocation is not provided through the browser's location feature.

## Cloud Tunneling

Cloudflared was used in the controlled lab environment to create a tunnel to the locally running service on port 8080.

This demonstrated how a locally hosted service can be accessed through a tunnel during authorized testing.

## Location Technologies

The project also explored the differences between:

- GPS location
- Browser geolocation
- IP-based geolocation
- Wi-Fi positioning
- Cell-tower positioning

These technologies use different sources of information and can provide different levels of location accuracy.

## Privacy and Security

Location information can be sensitive. This lab helped demonstrate why users should understand location permission requests and carefully consider before granting access to precise location information.

## Ethical Scope

All testing was performed in a controlled and authorized environment using devices and systems owned or controlled by the researcher.

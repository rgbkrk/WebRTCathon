WebRTCathon
===========

If you haven't already, we recommend reading the
[HTML 5 Rocks posting about WebRTC](http://www.html5rocks.com/en/tutorials/webrtc/basics).

The main webrtc site is located at [webrtc.org](http://www.webrtc.org/)

Feel free to make any pull requests to change this up and add components. Adding to the wiki is great as well.

# Purpose

Enable people to run their own support infrastructure for WebRTC.

# Goals

These goals were set by one person, you can set your own. :P

* Deploy server side functionality to support WebRTC, including
  * User discovery and communication.
  * Signaling.
  * NAT/firewall traversal.
  * Relay servers in case peer-to-peer communication fails.
* Deploy the [apprtc.appspot.com](http://apprtc.appspot.com/) application.
* Fork the apprtc app

# STUN Server

The STUN server acts as the medium to directly connect peers.

This blog post was provides a good tutorial on settings up a STUN server: https://www.dialogic.com/den/forums/t/10238.aspx

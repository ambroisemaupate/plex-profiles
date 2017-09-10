# Customized Plex media server profiles

On Linux: install/override profiles in `/usr/lib/plexmediaserver/Resources/Profiles`

- *Chromecast Ultra* profile :
   Allow HEVC, MKV with external subtitles to be *direct played*. Override `Chromecast.xml`, if any issue with subtitle
   or sound revert to original profile (`Chromecast.xml.bak`)

## References

- https://developers.google.com/cast/docs/media#audio-codecs
- https://forums.plex.tv/discussion/244663/chromecast-ultra-profile-doesnt-support-hevc/p2
# hugo-funkwhale-shortcode

A shortcode for Hugo static site generator to include audio hosted on a **Funkwhale** instance. Funkwhale is a community-driven project that lets you listen and share music and audio within a decentralized, open and federated network.

### Usage

Insert the _Shortcode_ in your Markdown content...

**Simplified syntax**

```
{{< funkwhale open.audio 84899 >}}
```
Only tracks (no album), and only default config.

**Complete syntax**

```
{{< funkwhale host="open.audio" id="84899" type="track" >}}
```
You can specify `type` (track or album) and `height` (numeral value: default 138). With no `type` it fallback to track value.

**Syntax for album**

```
{{< funkwhale host="open.audio" id="8493" type="album"  height="330 >}}
```

Note: you _must_ adjust the `height`, there is no default value suitable for albums.

### Privacy

Funckwhale by itself use absolutely no cookies, no trackers.

### References

- [Funkwhale](https://funkwhale.audio/)
- [Hugo](https://gohugo.io)
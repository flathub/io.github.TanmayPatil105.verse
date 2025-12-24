# verse

___Get currently playing Spotify song lyrics___

A simple application that fetches lyrics of the song currently playing on Spotify and displays it on a beautiful user interface. Features:

- Simple, easy to use interface
- Paginated view displays previously played songs
- Multiple themes

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub io.github.TanmayPatil105.verse
flatpak run io.github.TanmayPatil105.verse
```

## Building

```
git clone git@github.com:flathub/io.github.TanmayPatil105.verse.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.TanmayPatil105.verse.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Python

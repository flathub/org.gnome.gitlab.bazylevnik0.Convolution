# Convolution

___Maze escaping game___

Logic game about escaping from a maze. Mazes are generative and in all resets are new. PC opponents with simple AIs trying to eat the player and do not gives opportunity to escape from the maze.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub org.gnome.gitlab.bazylevnik0.Convolution
flatpak run org.gnome.gitlab.bazylevnik0.Convolution
```

## Building

```bash
git clone git@github.com:flathub/org.gnome.gitlab.bazylevnik0.Convolution.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.gnome.gitlab.bazylevnik0.Convolution.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, JavaScript, TypeScript

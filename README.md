# Griffteam Oběd — Content

Binary content (images, music, sounds) for the Griffteam Oběd application.

This repo is included as a git submodule at `content/` in the main [Obed](https://github.com/pavelfuksa/Obedv2) repository.

## Structure

```
dungeon/            ← Room images, spaceship minigame art + music
music/              ← Game music
tasks_images/       ← Daily task images  
ai_generated/       ← AI-generated game images
komiks/             ← Original comics (other, vilobed)
polls/              ← Poll images
griffteam-logo.png  ← Logo
```

## Usage

```bash
# Clone main repo WITH content:
git clone --recurse-submodules https://github.com/pavelfuksa/Obedv2.git

# If you already cloned without submodules:
git submodule update --init --recursive
```

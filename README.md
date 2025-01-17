Use this repository as a template to start a new Haxepunk project.

Haxepunk source code can be found at the `dev` branch. This branch pulls the library in as a submodule.

### Setup
```
haxelib install lime
haxelib install openfl
haxelib run lime setup
```

### How to use
- Run `git submodule update --init --recursive` to pull haxepunk source
- Edit `project.xml`:
  - Set `<meta>` attributes as appropriate
  - If you don't want to use the preloader, edit the `<app>` tag to remove the `preloader` attribute
- Open the project folder in VSCode, select build target, and run
- Builds will be placed in the `export/` folder

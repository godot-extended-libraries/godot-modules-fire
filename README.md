# modules

```
git clone https://github.com/godot-extended-libraries/godot-modules-fire.git
git clone https://github.com/Xrayez/godot.git -b modules-search-path-3.2 godot-modules
cd godot-modules
scons p=windows custom_modules=../godot-modules-fire -j6

#### To install netlist viewer

```
1. sudo apt install npm
2. git clone https://github.com/nturley/netlistsvg
3. cd netlistsvg
4. npm install --legacy-peer-deps
#npm install # install dependencies
5. sudo npm install -g . # install netlistsvg to system
```
#### To uninstall
```
sudo npm uninstall -g netlistsvg # uninstall from system
```

# to view
```
netlistsvg input_json_file [-o output_svg_file] [--skin skin_file]
```

google-map
==========

## clone into an empty folder

```
mkdir google-map-flado
cd google-map-flado
git clone https://github.com/flado/google-map.git
```

## Install Bower components

```
cd google-map
bower install
```

## Install a HTTP server

```
npm install http-server -g
```

## Start the HTTP server in the parent (non-git repo) folder to serve static pages

```
cd..
http-server
```

## Go in the browser and see how it looks like

```
http://localhost:8080/googl-map/demo.html
http://localhost:8080/googl-map/demo-autocomplete.html
```

==========

See the [component page](http://googlewebcomponents.github.io/google-map) for more information.


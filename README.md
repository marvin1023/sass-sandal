# sass sandal

a basic sass library, included reset css and some basic mixin and so on.

## Install

### Git

```
git clone git@github.com:marvin1023/sass-sandal.git
```

### npm

```
npm install sass-sandal --save-dev
```

## Usage

### core scss

Import `dist/_core.scss` included all scss files in core folder.

```scss
// If you installed via Npm
@import "node_modules/sass-sandal/dist/core";
```

### function scss

Import `dist/_function.scss` excluded the reset files in core folder.

```scss
// If you installed via Npm
@import "node_modules/sass-sandal/dist/function";
```

### ext scss

if you need the basic @font-face icon, you can Import `dist/ext/font-face/font-face` 

```scss
// If you installed via Npm
// font-face
@import "node_modules/sass-sandal/dist/ext/font-face/font-face";
// 
```

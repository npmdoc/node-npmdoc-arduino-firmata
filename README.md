# api documentation for  [arduino-firmata (v0.3.4)](https://github.com/shokai/node-arduino-firmata)  [![npm package](https://img.shields.io/npm/v/npmdoc-arduino-firmata.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-arduino-firmata) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-arduino-firmata.svg)](https://travis-ci.org/npmdoc/node-npmdoc-arduino-firmata)
#### Arduino Firmata implementation for Node.js

[![NPM](https://nodei.co/npm/arduino-firmata.png?downloads=true)](https://www.npmjs.com/package/arduino-firmata)

[![apidoc](https://npmdoc.github.io/node-npmdoc-arduino-firmata/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-arduino-firmata%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-arduino-firmata/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-arduino-firmata/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-arduino-firmata/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sho Hashimoto",
        "email": "hashimoto@shokai.org"
    },
    "bugs": {
        "url": "https://github.com/shokai/node-arduino-firmata/issues"
    },
    "dependencies": {
        "debug": "*",
        "eventemitter2": "*",
        "serialport": "*"
    },
    "description": "Arduino Firmata implementation for Node.js",
    "devDependencies": {
        "async": "*",
        "coffee-errors": "*",
        "coffee-script": "^1.8",
        "grunt": "*",
        "grunt-cli": "*",
        "grunt-coffeelint": "*",
        "grunt-contrib-coffee": "*",
        "grunt-contrib-watch": "*",
        "grunt-notify": "*",
        "grunt-simple-mocha": "*",
        "mocha": "*",
        "socket.io": "*"
    },
    "directories": {
        "test": "tests"
    },
    "dist": {
        "shasum": "bc3be8a3550c8fb4195ed380031c5cbc72106773",
        "tarball": "https://registry.npmjs.org/arduino-firmata/-/arduino-firmata-0.3.4.tgz"
    },
    "gitHead": "4ff8e4c21db341cfe19fc04903b2b5568c7aabac",
    "homepage": "https://github.com/shokai/node-arduino-firmata",
    "keywords": [
        "arduino",
        "firmata"
    ],
    "license": "MIT",
    "main": "lib/arduino-firmata.js",
    "maintainers": [
        {
            "name": "shokai",
            "email": "hashimoto@shokai.org"
        }
    ],
    "name": "arduino-firmata",
    "optionalDependencies": {},
    "private": false,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/shokai/node-arduino-firmata.git"
    },
    "scripts": {
        "build": "grunt build",
        "test": "grunt test",
        "watch": "grunt"
    },
    "version": "0.3.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module arduino-firmata](#apidoc.module.arduino-firmata)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.</span>EventEmitter2 (conf)](#apidoc.element.arduino-firmata.EventEmitter2)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.</span>list (callback)](#apidoc.element.arduino-firmata.list)
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>ANALOG
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>ANALOG_MESSAGE
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>DIGITAL_MESSAGE
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>END_SYSEX
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>HIGH
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>I2C
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>INPUT
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>LOW
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>MAX_DATA_BYTES
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>OUTPUT
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>PWM
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>REPORT_ANALOG
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>REPORT_DIGITAL
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>REPORT_VERSION
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>SERVO
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>SET_PIN_MODE
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>SHIFT
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>START_SYSEX
1.  number <span class="apidocSignatureSpan">arduino-firmata.</span>SYSTEM_RESET
1.  object <span class="apidocSignatureSpan">arduino-firmata.</span>Status
1.  object <span class="apidocSignatureSpan">arduino-firmata.</span>__super__

#### [module arduino-firmata.EventEmitter2](#apidoc.module.arduino-firmata.EventEmitter2)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.</span>EventEmitter2 (conf)](#apidoc.element.arduino-firmata.EventEmitter2.EventEmitter2)

#### [module arduino-firmata.__super__](#apidoc.module.arduino-firmata.__super__)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_many (event, ttl, fn, prepend)](#apidoc.element.arduino-firmata.__super__._many)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_on (type, listener, prepend)](#apidoc.element.arduino-firmata.__super__._on)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_onAny (fn, prepend)](#apidoc.element.arduino-firmata.__super__._onAny)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_once (event, fn, prepend)](#apidoc.element.arduino-firmata.__super__._once)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>addListener (type, listener)](#apidoc.element.arduino-firmata.__super__.addListener)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>emit ()](#apidoc.element.arduino-firmata.__super__.emit)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>emitAsync ()](#apidoc.element.arduino-firmata.__super__.emitAsync)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>eventNames ()](#apidoc.element.arduino-firmata.__super__.eventNames)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>listenerCount (type)](#apidoc.element.arduino-firmata.__super__.listenerCount)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>listeners (type)](#apidoc.element.arduino-firmata.__super__.listeners)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>listenersAny ()](#apidoc.element.arduino-firmata.__super__.listenersAny)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>many (event, ttl, fn)](#apidoc.element.arduino-firmata.__super__.many)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>off (type, listener)](#apidoc.element.arduino-firmata.__super__.off)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>offAny (fn)](#apidoc.element.arduino-firmata.__super__.offAny)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>on (type, listener)](#apidoc.element.arduino-firmata.__super__.on)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>onAny (fn)](#apidoc.element.arduino-firmata.__super__.onAny)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>once (event, fn)](#apidoc.element.arduino-firmata.__super__.once)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependAny (fn)](#apidoc.element.arduino-firmata.__super__.prependAny)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependListener (type, listener)](#apidoc.element.arduino-firmata.__super__.prependListener)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependMany (event, ttl, fn)](#apidoc.element.arduino-firmata.__super__.prependMany)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependOnceListener (event, fn)](#apidoc.element.arduino-firmata.__super__.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>removeAllListeners (type)](#apidoc.element.arduino-firmata.__super__.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>removeListener (type, listener)](#apidoc.element.arduino-firmata.__super__.removeListener)
1.  [function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>setMaxListeners (n)](#apidoc.element.arduino-firmata.__super__.setMaxListeners)
1.  string <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>delimiter
1.  string <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>event



# <a name="apidoc.module.arduino-firmata"></a>[module arduino-firmata](#apidoc.module.arduino-firmata)

#### <a name="apidoc.element.arduino-firmata.EventEmitter2"></a>[function <span class="apidocSignatureSpan">arduino-firmata.</span>EventEmitter2 (conf)](#apidoc.element.arduino-firmata.EventEmitter2)
- description and source-code
```javascript
function EventEmitter(conf) {
  this._events = {};
  this.newListener = false;
  this.verboseMemoryLeak = false;
  configure.call(this, conf);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.list"></a>[function <span class="apidocSignatureSpan">arduino-firmata.</span>list (callback)](#apidoc.element.arduino-firmata.list)
- description and source-code
```javascript
list = function (callback) {
  return serialport.list(function(err, ports) {
    var devices, j, len, port;
    if (err) {
      return callback(err);
    }
    devices = [];
    for (j = 0, len = ports.length; j < len; j++) {
      port = ports[j];
      if (/usb|acm|com|ama\d+/i.test(port.comName)) {
        devices.push(port.comName);
      }
    }
    return callback(null, devices);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.arduino-firmata.EventEmitter2"></a>[module arduino-firmata.EventEmitter2](#apidoc.module.arduino-firmata.EventEmitter2)

#### <a name="apidoc.element.arduino-firmata.EventEmitter2.EventEmitter2"></a>[function <span class="apidocSignatureSpan">arduino-firmata.</span>EventEmitter2 (conf)](#apidoc.element.arduino-firmata.EventEmitter2.EventEmitter2)
- description and source-code
```javascript
function EventEmitter(conf) {
  this._events = {};
  this.newListener = false;
  this.verboseMemoryLeak = false;
  configure.call(this, conf);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.arduino-firmata.__super__"></a>[module arduino-firmata.__super__](#apidoc.module.arduino-firmata.__super__)

#### <a name="apidoc.element.arduino-firmata.__super__._many"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_many (event, ttl, fn, prepend)](#apidoc.element.arduino-firmata.__super__._many)
- description and source-code
```javascript
_many = function (event, ttl, fn, prepend) {
  var self = this;

  if (typeof fn !== 'function') {
    throw new Error('many only accepts instances of Function');
  }

  function listener() {
    if (--ttl === 0) {
      self.off(event, listener);
    }
    return fn.apply(this, arguments);
  }

  listener._origin = fn;

  this._on(event, listener, prepend);

  return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__._on"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_on (type, listener, prepend)](#apidoc.element.arduino-firmata.__super__._on)
- description and source-code
```javascript
_on = function (type, listener, prepend) {
  if (typeof type === 'function') {
    this._onAny(type, listener);
    return this;
  }

  if (typeof listener !== 'function') {
    throw new Error('on only accepts instances of Function');
  }
  this._events || init.call(this);

  // To avoid recursion in the case that type == "newListeners"! Before
  // adding it to the listeners, first emit "newListeners".
  this.emit('newListener', type, listener);

  if (this.wildcard) {
    growListenerTree.call(this, type, listener);
    return this;
  }

  if (!this._events[type]) {
    // Optimize the case of one listener. Don't need the extra array object.
    this._events[type] = listener;
  }
  else {
    if (typeof this._events[type] === 'function') {
      // Change to array.
      this._events[type] = [this._events[type]];
    }

    // If we've already got an array, just add
    if(prepend){
      this._events[type].unshift(listener);
    }else{
      this._events[type].push(listener);
    }

    // Check for listener leak
    if (
      !this._events[type].warned &&
      this._maxListeners > 0 &&
      this._events[type].length > this._maxListeners
    ) {
      this._events[type].warned = true;
      logPossibleMemoryLeak.call(this, this._events[type].length, type);
    }
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__._onAny"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_onAny (fn, prepend)](#apidoc.element.arduino-firmata.__super__._onAny)
- description and source-code
```javascript
_onAny = function (fn, prepend){
  if (typeof fn !== 'function') {
    throw new Error('onAny only accepts instances of Function');
  }

  if (!this._all) {
    this._all = [];
  }

  // Add the function to the event listener collection.
  if(prepend){
    this._all.unshift(fn);
  }else{
    this._all.push(fn);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__._once"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>_once (event, fn, prepend)](#apidoc.element.arduino-firmata.__super__._once)
- description and source-code
```javascript
_once = function (event, fn, prepend) {
  this._many(event, 1, fn, prepend);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.addListener"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>addListener (type, listener)](#apidoc.element.arduino-firmata.__super__.addListener)
- description and source-code
```javascript
addListener = function (type, listener) {
  return this._on(type, listener, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.emit"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>emit ()](#apidoc.element.arduino-firmata.__super__.emit)
- description and source-code
```javascript
emit = function () {

  this._events || init.call(this);

  var type = arguments[0];

  if (type === 'newListener' && !this.newListener) {
    if (!this._events.newListener) {
      return false;
    }
  }

  var al = arguments.length;
  var args,l,i,j;
  var handler;

  if (this._all && this._all.length) {
    handler = this._all.slice();
    if (al > 3) {
      args = new Array(al);
      for (j = 0; j < al; j++) args[j] = arguments[j];
    }

    for (i = 0, l = handler.length; i < l; i++) {
      this.event = type;
      switch (al) {
      case 1:
        handler[i].call(this, type);
        break;
      case 2:
        handler[i].call(this, type, arguments[1]);
        break;
      case 3:
        handler[i].call(this, type, arguments[1], arguments[2]);
        break;
      default:
        handler[i].apply(this, args);
      }
    }
  }

  if (this.wildcard) {
    handler = [];
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    searchListenerTree.call(this, handler, ns, this.listenerTree, 0);
  } else {
    handler = this._events[type];
    if (typeof handler === 'function') {
      this.event = type;
      switch (al) {
      case 1:
        handler.call(this);
        break;
      case 2:
        handler.call(this, arguments[1]);
        break;
      case 3:
        handler.call(this, arguments[1], arguments[2]);
        break;
      default:
        args = new Array(al - 1);
        for (j = 1; j < al; j++) args[j - 1] = arguments[j];
        handler.apply(this, args);
      }
      return true;
    } else if (handler) {
      // need to make copy of handlers because list can change in the middle
      // of emit call
      handler = handler.slice();
    }
  }

  if (handler && handler.length) {
    if (al > 3) {
      args = new Array(al - 1);
      for (j = 1; j < al; j++) args[j - 1] = arguments[j];
    }
    for (i = 0, l = handler.length; i < l; i++) {
      this.event = type;
      switch (al) {
      case 1:
        handler[i].call(this);
        break;
      case 2:
        handler[i].call(this, arguments[1]);
        break;
      case 3:
        handler[i].call(this, arguments[1], arguments[2]);
        break;
      default:
        handler[i].apply(this, args);
      }
    }
    return true;
  } else if (!this._all && type === 'error') {
    if (arguments[1] instanceof Error) {
      throw arguments[1]; // Unhandled 'error' event
    } else {
      throw new Error("Uncaught, unspecified 'error' event.");
    }
    return false;
  }

  return !!this._all;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.emitAsync"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>emitAsync ()](#apidoc.element.arduino-firmata.__super__.emitAsync)
- description and source-code
```javascript
emitAsync = function () {

  this._events || init.call(this);

  var type = arguments[0];

  if (type === 'newListener' && !this.newListener) {
      if (!this._events.newListener) { return Promise.resolve([false]); }
  }

  var promises= [];

  var al = arguments.length;
  var args,l,i,j;
  var handler;

  if (this._all) {
    if (al > 3) {
      args = new Array(al);
      for (j = 1; j < al; j++) args[j] = arguments[j];
    }
    for (i = 0, l = this._all.length; i < l; i++) {
      this.event = type;
      switch (al) {
      case 1:
        promises.push(this._all[i].call(this, type));
        break;
      case 2:
        promises.push(this._all[i].call(this, type, arguments[1]));
        break;
      case 3:
        promises.push(this._all[i].call(this, type, arguments[1], arguments[2]));
        break;
      default:
        promises.push(this._all[i].apply(this, args));
      }
    }
  }

  if (this.wildcard) {
    handler = [];
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    searchListenerTree.call(this, handler, ns, this.listenerTree, 0);
  } else {
    handler = this._events[type];
  }

  if (typeof handler === 'function') {
    this.event = type;
    switch (al) {
    case 1:
      promises.push(handler.call(this));
      break;
    case 2:
      promises.push(handler.call(this, arguments[1]));
      break;
    case 3:
      promises.push(handler.call(this, arguments[1], arguments[2]));
      break;
    default:
      args = new Array(al - 1);
      for (j = 1; j < al; j++) args[j - 1] = arguments[j];
      promises.push(handler.apply(this, args));
    }
  } else if (handler && handler.length) {
    handler = handler.slice();
    if (al > 3) {
      args = new Array(al - 1);
      for (j = 1; j < al; j++) args[j - 1] = arguments[j];
    }
    for (i = 0, l = handler.length; i < l; i++) {
      this.event = type;
      switch (al) {
      case 1:
        promises.push(handler[i].call(this));
        break;
      case 2:
        promises.push(handler[i].call(this, arguments[1]));
        break;
      case 3:
        promises.push(handler[i].call(this, arguments[1], arguments[2]));
        break;
      default:
        promises.push(handler[i].apply(this, args));
      }
    }
  } else if (!this._all && type === 'error') {
    if (arguments[1] instanceof Error) {
      return Promise.reject(arguments[1]); // Unhandled 'error' event
    } else {
      return Promise.reject("Uncaught, unspecified 'error' event.");
    }
  }

  return Promise.all(promises);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.eventNames"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>eventNames ()](#apidoc.element.arduino-firmata.__super__.eventNames)
- description and source-code
```javascript
eventNames = function (){
  return Object.keys(this._events);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.listenerCount"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>listenerCount (type)](#apidoc.element.arduino-firmata.__super__.listenerCount)
- description and source-code
```javascript
listenerCount = function (type) {
  return this.listeners(type).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.listeners"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>listeners (type)](#apidoc.element.arduino-firmata.__super__.listeners)
- description and source-code
```javascript
listeners = function (type) {
  if (this.wildcard) {
    var handlers = [];
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    searchListenerTree.call(this, handlers, ns, this.listenerTree, 0);
    return handlers;
  }

  this._events || init.call(this);

  if (!this._events[type]) this._events[type] = [];
  if (!isArray(this._events[type])) {
    this._events[type] = [this._events[type]];
  }
  return this._events[type];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.listenersAny"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>listenersAny ()](#apidoc.element.arduino-firmata.__super__.listenersAny)
- description and source-code
```javascript
listenersAny = function () {

  if(this._all) {
    return this._all;
  }
  else {
    return [];
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.many"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>many (event, ttl, fn)](#apidoc.element.arduino-firmata.__super__.many)
- description and source-code
```javascript
many = function (event, ttl, fn) {
  return this._many(event, ttl, fn, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.off"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>off (type, listener)](#apidoc.element.arduino-firmata.__super__.off)
- description and source-code
```javascript
off = function (type, listener) {
  if (typeof listener !== 'function') {
    throw new Error('removeListener only takes instances of Function');
  }

  var handlers,leafs=[];

  if(this.wildcard) {
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    leafs = searchListenerTree.call(this, null, ns, this.listenerTree, 0);
  }
  else {
    // does not use listeners(), so no side effect of creating _events[type]
    if (!this._events[type]) return this;
    handlers = this._events[type];
    leafs.push({_listeners:handlers});
  }

  for (var iLeaf=0; iLeaf<leafs.length; iLeaf++) {
    var leaf = leafs[iLeaf];
    handlers = leaf._listeners;
    if (isArray(handlers)) {

      var position = -1;

      for (var i = 0, length = handlers.length; i < length; i++) {
        if (handlers[i] === listener ||
          (handlers[i].listener && handlers[i].listener === listener) ||
          (handlers[i]._origin && handlers[i]._origin === listener)) {
          position = i;
          break;
        }
      }

      if (position < 0) {
        continue;
      }

      if(this.wildcard) {
        leaf._listeners.splice(position, 1);
      }
      else {
        this._events[type].splice(position, 1);
      }

      if (handlers.length === 0) {
        if(this.wildcard) {
          delete leaf._listeners;
        }
        else {
          delete this._events[type];
        }
      }

      this.emit("removeListener", type, listener);

      return this;
    }
    else if (handlers === listener ||
      (handlers.listener && handlers.listener === listener) ||
      (handlers._origin && handlers._origin === listener)) {
      if(this.wildcard) {
        delete leaf._listeners;
      }
      else {
        delete this._events[type];
      }

      this.emit("removeListener", type, listener);
    }
  }

  function recursivelyGarbageCollect(root) {
    if (root === undefined) {
      return;
    }
    var keys = Object.keys(root);
    for (var i in keys) {
      var key = keys[i];
      var obj = root[key];
      if ((obj instanceof Function) || (typeof obj !== "object") || (obj === null))
        continue;
      if (Object.keys(obj).length > 0) {
        recursivelyGarbageCollect(root[key]);
      }
      if (Object.keys(obj).length === 0) {
        delete root[key];
      }
    }
  }
  recursivelyGarbageCollect(this.listenerTree);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.offAny"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>offAny (fn)](#apidoc.element.arduino-firmata.__super__.offAny)
- description and source-code
```javascript
offAny = function (fn) {
  var i = 0, l = 0, fns;
  if (fn && this._all && this._all.length > 0) {
    fns = this._all;
    for(i = 0, l = fns.length; i < l; i++) {
      if(fn === fns[i]) {
        fns.splice(i, 1);
        this.emit("removeListenerAny", fn);
        return this;
      }
    }
  } else {
    fns = this._all;
    for(i = 0, l = fns.length; i < l; i++)
      this.emit("removeListenerAny", fns[i]);
    this._all = [];
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.on"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>on (type, listener)](#apidoc.element.arduino-firmata.__super__.on)
- description and source-code
```javascript
on = function (type, listener) {
  return this._on(type, listener, false);
}
```
- example usage
```shell
...
'''javascript
var ArduinoFirmata = require('arduino-firmata');
var arduino = new ArduinoFirmata();

arduino.connect(); // use default arduino
arduino.connect('/dev/tty.usb-device-name');

arduino.on('connect', function(){

  console.log("board version"+arduino.boardVersion);
  // your-code-here

});
'''
...
```

#### <a name="apidoc.element.arduino-firmata.__super__.onAny"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>onAny (fn)](#apidoc.element.arduino-firmata.__super__.onAny)
- description and source-code
```javascript
onAny = function (fn) {
  return this._onAny(fn, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.once"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>once (event, fn)](#apidoc.element.arduino-firmata.__super__.once)
- description and source-code
```javascript
once = function (event, fn) {
  return this._once(event, fn, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.prependAny"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependAny (fn)](#apidoc.element.arduino-firmata.__super__.prependAny)
- description and source-code
```javascript
prependAny = function (fn) {
  return this._onAny(fn, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.prependListener"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependListener (type, listener)](#apidoc.element.arduino-firmata.__super__.prependListener)
- description and source-code
```javascript
prependListener = function (type, listener) {
  return this._on(type, listener, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.prependMany"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependMany (event, ttl, fn)](#apidoc.element.arduino-firmata.__super__.prependMany)
- description and source-code
```javascript
prependMany = function (event, ttl, fn) {
  return this._many(event, ttl, fn, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.prependOnceListener"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>prependOnceListener (event, fn)](#apidoc.element.arduino-firmata.__super__.prependOnceListener)
- description and source-code
```javascript
prependOnceListener = function (event, fn) {
  return this._once(event, fn, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.removeAllListeners"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>removeAllListeners (type)](#apidoc.element.arduino-firmata.__super__.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function (type) {
  if (arguments.length === 0) {
    !this._events || init.call(this);
    return this;
  }

  if (this.wildcard) {
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    var leafs = searchListenerTree.call(this, null, ns, this.listenerTree, 0);

    for (var iLeaf=0; iLeaf<leafs.length; iLeaf++) {
      var leaf = leafs[iLeaf];
      leaf._listeners = null;
    }
  }
  else if (this._events) {
    this._events[type] = null;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.removeListener"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>removeListener (type, listener)](#apidoc.element.arduino-firmata.__super__.removeListener)
- description and source-code
```javascript
removeListener = function (type, listener) {
  if (typeof listener !== 'function') {
    throw new Error('removeListener only takes instances of Function');
  }

  var handlers,leafs=[];

  if(this.wildcard) {
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    leafs = searchListenerTree.call(this, null, ns, this.listenerTree, 0);
  }
  else {
    // does not use listeners(), so no side effect of creating _events[type]
    if (!this._events[type]) return this;
    handlers = this._events[type];
    leafs.push({_listeners:handlers});
  }

  for (var iLeaf=0; iLeaf<leafs.length; iLeaf++) {
    var leaf = leafs[iLeaf];
    handlers = leaf._listeners;
    if (isArray(handlers)) {

      var position = -1;

      for (var i = 0, length = handlers.length; i < length; i++) {
        if (handlers[i] === listener ||
          (handlers[i].listener && handlers[i].listener === listener) ||
          (handlers[i]._origin && handlers[i]._origin === listener)) {
          position = i;
          break;
        }
      }

      if (position < 0) {
        continue;
      }

      if(this.wildcard) {
        leaf._listeners.splice(position, 1);
      }
      else {
        this._events[type].splice(position, 1);
      }

      if (handlers.length === 0) {
        if(this.wildcard) {
          delete leaf._listeners;
        }
        else {
          delete this._events[type];
        }
      }

      this.emit("removeListener", type, listener);

      return this;
    }
    else if (handlers === listener ||
      (handlers.listener && handlers.listener === listener) ||
      (handlers._origin && handlers._origin === listener)) {
      if(this.wildcard) {
        delete leaf._listeners;
      }
      else {
        delete this._events[type];
      }

      this.emit("removeListener", type, listener);
    }
  }

  function recursivelyGarbageCollect(root) {
    if (root === undefined) {
      return;
    }
    var keys = Object.keys(root);
    for (var i in keys) {
      var key = keys[i];
      var obj = root[key];
      if ((obj instanceof Function) || (typeof obj !== "object") || (obj === null))
        continue;
      if (Object.keys(obj).length > 0) {
        recursivelyGarbageCollect(root[key]);
      }
      if (Object.keys(obj).length === 0) {
        delete root[key];
      }
    }
  }
  recursivelyGarbageCollect(this.listenerTree);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.arduino-firmata.__super__.setMaxListeners"></a>[function <span class="apidocSignatureSpan">arduino-firmata.__super__.</span>setMaxListeners (n)](#apidoc.element.arduino-firmata.__super__.setMaxListeners)
- description and source-code
```javascript
setMaxListeners = function (n) {
  if (n !== undefined) {
    this._maxListeners = n;
    if (!this._conf) this._conf = {};
    this._conf.maxListeners = n;
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
